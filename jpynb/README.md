# Anaconda Python with Jupyter Notebook Server

## Instructions

Anconda Python and Jupyter Notebook

Create file set_compose_env and enter
```
MY_NOTEBOOKS=<directory containing notebooks>
```
example `MY_NOTEBOOKS=/Users/jim/Desktop/my_source_files`

Change working directory to directory containing these files.

```
# set environment variable MY_NOTEBOOKS
source ./set_compose_env

# start up Jupyter Notebook server
docker-compose up -d

# launch broswer to connect to Jupyter Notebook server
./launch_jpynb
```

