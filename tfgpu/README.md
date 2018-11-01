# Anaconda Python with TensorFlow (GPU) (WORK-IN-PROGRESS)

## Set up

Create file set_env_variables:
```
# set password and options for Jupyter Notebook
export NOTEBOOK_PASSWORD=sha1:<hashed password>
```


## Instructions

Anconda Python and Jupyter Notebook

### To start container:
```
start_dss tfgpu [source_code_dir]
```
`source_code_dir`: optional parameter, if missing assumes current working directory.


### To stop conatiner:
```
stop_dss tfgpu
```

### Limitations:
* Notebook authentican disabled.
* Slow performance during conda create if directory for conda environment is outside of container
