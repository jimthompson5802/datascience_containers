# Anaconda Python with Jupyter Notebook Server

## Additional Packages
* xgboost



## Set up

Pull image from dockerhub.com
```
pull_image xgboost
```

## Instructions

Anconda Python and Jupyter Notebook

### To start container:
```
start_dss xgboost [source_code_dir]
```
`source_code_dir`: optional parameter, if missing assumes current working directory.

### To launch web browser (MacOS only) or print port number to connect (AWS Linux)
```
launch_dss xgboost
```

### To stop conatiner:
```
stop_dss xgboost
```

### Limitations:
* Notebook authentician disabled.


