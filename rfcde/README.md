# Anaconda Python with Jupyter Notebook Server

## Additional Packages
* rfcde



## Set up

Pull image from dockerhub.com
```
pull_image rfcde
```

## Instructions

Anconda Python and Jupyter Notebook

### To start container:
```
start_dss rfcde [source_code_dir]
```
`source_code_dir`: optional parameter, if missing assumes current working directory.

### To launch web browser (MacOS only) or print port number to connect (AWS Linux)
```
launch_dss rfcde
```

### To stop conatiner:
```
stop_dss rfcde
```

### Limitations:
* Notebook authentican disabled.


