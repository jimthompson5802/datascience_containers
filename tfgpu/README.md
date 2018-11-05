# Tensorflow (GPU) with Jupyter Notebook

## DockerHub
`docker pull dsimages/tfgpu`

## Set up

Create file set_env_variables:
```
# set password and options for Jupyter Notebook
export NOTEBOOK_PASSWORD=sha1:<hashed password>
```

See instructions in [wiki](https://github.com/jimthompson5802/datascience_containers/wiki/Hashed-Password-for-Jupyter-Notebooks).

## Instructions

### To start container:
```
start_dss tfgpu [source_code_dir]
```
`source_code_dir`: optional parameter, if missing assumes current working directory.


### To launch web browser (MacOS only) or print port number to connect (AWS Linux)
```
launch_dss tfgpu
```

### To stop conatiner:
```
stop_dss tfgpu
```

### Limitations:
* Contains subset of Anaconda distribution.  Avaialable packages: pandas, numpy, scipy, scikit-learn
