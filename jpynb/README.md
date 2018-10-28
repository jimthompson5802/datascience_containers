# Anaconda Python with Jupyter Notebook Server

## Set up

Create file set_env_variables:
```
# set password and options for Jupyter Notebook
export NOTEBOOK_PASSWORD=`python -c"from notebook.auth import passwd;print(passwd('<password>'))"`
```
example:
`export NOTEBOOK_PASSWORD=`python -c"from notebook.auth import passwd;print(passwd('your_password'))"`

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
