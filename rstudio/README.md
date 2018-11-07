# RStudio Server (Open Source)

## Set up

Pull image from dockerhub.com
```
pull_image jpynb
```


## Instructions 

### To start container:
```
start_dss rstudio [source_code_dir]
```
`source_code_dir`: optional parameter, if missing assumes current working directory.


### To launch web browser (MacOS only) or print port number to connect (AWS Linux)
```
launch_dss rstudio
```

Login with user name `rstudio`, password `rstudio_pw`


### To stop conatiner:
```
stop_dss rstudio
```

### Limitations:
* Rstudio user set to constant value.
