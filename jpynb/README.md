# Anaconda Python with Jupyter Notebook Server

## Instructions

Anconda Python and Jupyter Notebook

Create file set_compose_env:
```
MY_NOTEBOOKS=<directory containing notebooks>
```

Change working directory to directory containing these files.

```
# set environment variable MY_NOTEBOOKS
source ./set_compose_env

# start up Jupyter Notebook server
docker-compose up -d

# launch broswer to connect to Jupyter Notebook server
./launch_jpynb
```

