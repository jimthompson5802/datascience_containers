# Anaconda Python with Jupyter Notebook Server

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
* Notebook authentican disabled.
* Slow performance during conda create if directory for conda environment is outside of container
