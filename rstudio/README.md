# RStudio Server (Open Source)

## Set up

RStudio Server 

Create file rstudio.env:
```
PASSWORD=<password for rstudio user>
```
example `PASSWORD=this_is_password`

## Instructions 

### To start container:
```
launch_dss rstudio [source_code_dir]
```
`source_code_dir`: optional parameter, if missing assumes current working directory.


### To stop conatiner:
```
stop_dss rstudio
```

### Limitations:
* Rstudio authentication dependent of static password stored in rstudio.env
