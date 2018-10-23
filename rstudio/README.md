# RStudio Server (Open Source)

## Instructions

RStudio Server 

Create file rstudio.env:
```
PASSWORD=<password for rstudio user>
```
example `PASSWORD=this_is_password`

Create file set_compose_env
```
MY_NOTEBOOKS=<directory containing source code>
```
example `MY_NOTEBOOKS=/User/jim/Desktop/my_source_code`

Change working directory to directory containing these files.

```
# set environment variable MY_NOTEBOOKS
source ./set_compose_env

# start up Rstudio Server container
docker-compose up -d

# launch browser to connect to RStudio Server
./launch_rstudio
```

