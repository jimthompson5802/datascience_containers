# Usage Instructions

Add bin directory to PATH environment variable

## docker compose

### To launch a container:
```
start_dss server [source_code_dir]
```
`server`: `jpynb` for Jupyter Notebook Server with Anaconda Python or `rstudio` for RStudio Server

`source_code_dir`: location of source code directory (optional).  If missing, assumes the current working directory.


### To stop a container:
```
stop_dss server
```
`server`: `jpynb` or `rstudio`

### Note:
* The bash script design assumes only one instance of any specific data science software stack is active.  For example, unpredictable results if two instances of `jpynb` are started.  However, it is possible to simulatenously run one instance of `jpynb` and one instance of `rstudio`.
* Depending on results of kubernetes testing, the above commands may get retired.

## kubernetes

### To launch a kubernetes service:
```
start_kub server [source_code_dir]
```
`server`: `jpynb` for Jupyter Notebook Server with Anaconda Python or `rstudio` for RStudio Server

`source_code_dir`: location of source code directory (optional).  If missing, assumes the current working directory.


### To stop a container:
```
stop_kub server
```
`server`: `jpynb` or `rstudio`

### Note:
* The bash script design assumes only one instance of any specific data science software stack is active.  For example, unpredictable results if two instances of `jpynb` are started.  However, it is possible to simulatenously run one instance of `jpynb` and one instance of `rstudio`.
* Depending on results of kubernetes testing, the above commands may get retired.
