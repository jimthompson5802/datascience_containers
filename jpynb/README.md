# Anaconda Python with Jupyter Notebook Server

## Additional Packages
* h2o
* xgboost
* lightgbm

## DockerHub
https://hub.docker.com/r/dsimages/jpynb/

## Set up

Create file set_env_variables:
```
# set password and options for Jupyter Notebook
export NOTEBOOK_PASSWORD=sha1:<hashed password>
```

See instructions in [wiki](https://github.com/jimthompson5802/datascience_containers/wiki/Hashed-Password-for-Jupyter-Notebooks).

## Instructions

Anconda Python and Jupyter Notebook

### To start container:
```
start_dss jpynb [source_code_dir]
```
`source_code_dir`: optional parameter, if missing assumes current working directory.


### To stop conatiner:
```
stop_dss jpynb
```

### Limitations:
Image build time:
* Mac about 17 minutes
* AWS Linux (p2.xlarge) about 18 minutes
