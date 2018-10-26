# RStudio Server (Open Source)

## Set up

RStudio Server 

Create file `set_env_variables`:
```
export PASSWORD=<password for rstudio user>
```
example `export PASSWORD=this_is_password`

## Instructions 

### To start container:
```
start_dss rstudio [source_code_dir]
```
`source_code_dir`: optional parameter, if missing assumes current working directory.


### To stop conatiner:
```
stop_dss rstudio
```

### Limitations:
* Rstudio authentication dependent of static password stored in rstudio.env
