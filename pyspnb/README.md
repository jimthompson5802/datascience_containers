# Anaconda Python with Apache Spark (Stand-alone)

## Set up

Create file set_env_variables:
```
# set password and options for Jupyter Notebook
export NOTEBOOK_PASSWORD=`python -c"from notebook.auth import passwd;print(passwd('<password>'))"`
```
example:
`export NOTEBOOK_PASSWORD=`python -c"from notebook.auth import passwd;print(passwd('your_password'))"`

## Instructions

Anconda Python and Jupyter Notebook and Stand-alone Spark

### To start container:
```
start_dss pyspnb [source_code_dir]
```
`source_code_dir`: optional parameter, if missing assumes current working directory.


### To stop conatiner:
```
stop_dss pyspnb
```

### Limitations:
* Notebook authentican disabled.
* Slow performance during conda create if directory for conda environment is outside of container
