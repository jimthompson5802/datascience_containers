# Anaconda Python with Jupyter Notebook Server

## Additional Packages
* h2o
* xgboost
* lightgbm



## Set up

Pull image from dockerhub.com
```
pull_image jpynb
```

## Instructions

Anconda Python and Jupyter Notebook

### To start container:
```
start_dss jpynb [source_code_dir]
```
`source_code_dir`: optional parameter, if missing assumes current working directory.

### To launch web browser (MacOS only) or print port number to connect (AWS Linux)
```
launch_dss jpynb
```

### To stop conatiner:
```
stop_dss jpynb
```

### Limitations:
* Notebook authentican disabled.
* Image build time: Mac about 17 minutes; AWS Linux (p2.xlarge) about 18 minutes


