# Anaconda Python with Apache Spark (Stand-alone)


## Set up

Pull image from dockerhub.com and create short-cut tag: 
```
docker pull dsimages/pyspnb
docker tag dsimages/pyspnb pyspnb
```

## Instructions

Anconda Python and Jupyter Notebook and Stand-alone Spark

### To start container:
```
start_dss pyspnb [source_code_dir]
```
`source_code_dir`: optional parameter, if missing assumes current working directory.


### To launch web browser (MacOS only) or print port number to connect (AWS Linux)
```
launch_dss pyspnb
```

### To stop conatiner:
```
stop_dss pyspnb
```

### Limitations:
* Notebook authentican disabled.
