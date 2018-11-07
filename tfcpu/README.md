# Tensorflow (CPU) with Jupyter Notebook

## Set up

Pull image from dockerhub.com
```
pull_image jpynb
```

## Instructions

### To start container:
```
start_dss tfcpu [source_code_dir]
```
`source_code_dir`: optional parameter, if missing assumes current working directory.


### To launch web browser (MacOS only) or print port number to connect (AWS Linux)
```
launch_dss tfcpu
```

### To stop conatiner:
```
stop_dss tfcpu
```

### Limitations:
* Notebook authentican disabled.
* Contains subset of Anaconda distribution.  Available packages: pandas, numpy, scipy, scikit-learn
