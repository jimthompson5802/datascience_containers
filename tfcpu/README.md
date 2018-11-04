# Tensorflow (CPU) with Jupyter Notebook

## Set up

Create file set_env_variables:
```
# set password and options for Jupyter Notebook
export NOTEBOOK_PASSWORD=sha1:<hashed password>
```


## Instructions

### To start container:
```
start_dss tfcpu [source_code_dir]
```
`source_code_dir`: optional parameter, if missing assumes current working directory.


### To stop conatiner:
```
stop_dss tfcpu
```

### Limitations:
* Contains subset of Anaconda distribution.  Avaialable packages: pandas, numpy, scipy, scikit-learn
