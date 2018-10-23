# Instructions

RStudio Server 

Create file rstudio.env:
```
PASSWORD=<password for rstudio user>
```

Create file set_compose_env
```
MY_NOTEBOOKS=<directory containing source code>
```



```
# set environment variable MY_NOTEBOOKS
source ./set_compose_env

# start up container
docker-compose up -d
```

