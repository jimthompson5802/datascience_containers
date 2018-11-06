# Tensorflow (GPU) with Jupyter Notebook

## Set up

Pull image from dockerhub.com and create short-cut tag: 
```
docker pull dsimages/tfgpu
docker tag dsimages/tfgpu
```

## Instructions

### To start container:
```
start_dss tfgpu [source_code_dir]
```
`source_code_dir`: optional parameter, if missing assumes current working directory.


### To launch web browser (MacOS only) or print port number to connect (AWS Linux)
```
launch_dss tfgpu
```

### To stop conatiner:
```
stop_dss tfgpu
```

### Limitations:
* Notebook authentican disabled.
* Contains subset of Anaconda distribution.  Avaialable packages: pandas, numpy, scipy, scikit-learn
