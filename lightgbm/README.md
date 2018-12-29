# Anaconda Python with Jupyter Notebook Server

## Additional Packages
* lightgbm



## Set up

Pull image from dockerhub.com
```
pull_image lightgbm
```

## Instructions

Anconda Python and Jupyter Notebook

### To start container:
```
start_dss lightgbm [source_code_dir]
```
`source_code_dir`: optional parameter, if missing assumes current working directory.

### To launch web browser (MacOS only) or print port number to connect (AWS Linux)
```
launch_dss lightgbm
```

### To stop conatiner:
```
stop_dss lightgbm
```

### Limitations:
* Notebook authentican disabled.


