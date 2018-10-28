# Usage Instructions

Add bin directory to PATH environment variable

## docker compose

### To launch a container:
```
# start running container
start_dss server [source_code_dir]

# launch web broswer for server
launch_dss server
```
`server`: server identifier, e.g., `jpynb`, `rstudio`, `pyspnb`, etc.

`source_code_dir`: location of source code directory (optional).  If missing, assumes the current working directory.


### To stop a container:
```
stop_dss server
```
`server`: server identifier

### Note:
* The bash script design assumes only one instance of any specific data science software stack is active.  For example, unpredictable results if two instances of `jpynb` are started.  However, it is possible to simulatenously run one instance of `jpynb` and one instance of `rstudio`.


## kubernetes

### To launch a kubernetes service:
```
# start container using kubernetes
start_kub server [source_code_dir]

# launch web server for server
launch_kub server
```
`server`: server identifier, e.g., `jpynb`, `rstudio`, `pyspnb`, etc.

`source_code_dir`: location of source code directory (optional).  If missing, assumes the current working directory.

### To stop a container:
```
stop_kub server
```
`server`: server identifier

### Note:
* The bash script design assumes only one instance of any specific data science software stack is active.  For example, unpredictable results if two instances of `jpynb` are started.  However, it is possible to simulatenously run one instance of `jpynb` and one instance of `rstudio`.

