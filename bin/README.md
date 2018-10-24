# Usage Instructions

Add bin directory to PATH environment variable

### To launch a container:
```
launch_dss server [source_code_dir]
```
`server`: `jpynb` for Jupyter Notebook Server with Anaconda Python or `rstudio` for RStudio Server

`source_code_dir`: location of source code directory (optional).  If missing, assumes the current working directory.


### To stop a container:
```
stop_dss server
```
`server`: `jpynb` or `rstudio`

### Note:
Depending on results of kubernetes testing, this method may get retired.
