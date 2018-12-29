# Anaconda Python with Jupyter Notebook Server

## Additional Packages
* h2o



## Set up

Pull image from dockerhub.com
```
pull_image h2opy
```

## Instructions

Anconda Python and Jupyter Notebook

### To start container:
```
start_dss h2opy [source_code_dir]
```
`source_code_dir`: optional parameter, if missing assumes current working directory.

### To launch web browser (MacOS only) or print port number to connect (AWS Linux)
```
launch_dss h2opy
```

### To stop conatiner:
```
stop_dss h2opy
```

### Limitations:
* Notebook authentican disabled.


