# Anaconda Python with Apache Spark (Stand-alone)

## Set up

Create file set_env_variables:
```
# set password and options for Jupyter Notebook
export NOTEBOOK_PASSWORD=sha1:<hashed password>
```

See instructions in [wiki](https://github.com/jimthompson5802/datascience_containers/wiki/Hashed-Password-for-Jupyter-Notebooks).

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
