# Data Science Software Stack Docker Prototype

Docker images providing the following data science software stacks for peronsal use:
* Anaconda Python with Jupyter Notebook
* Rstudio Server 
* Apache Spark (Stand-alone)
* Tensorflow (cpu and gpu versions)
* h2o
* xgboost
* lightgbm

See [wiki](https://github.com/jimthompson5802/datascience_containers/wiki) for additional information.

Built docker images can be found at [dockerhub.com](https://hub.docker.com/u/dsimages/)

## System Requirements:
* MacOS
* [Docker for Mac](https://store.docker.com/editions/community/docker-ce-desktop-mac) 18.06.1 ce (requires kubernetes enabled)
* Chrome Browser

## Directories:
* `bin` scripts to start and stop containers
* `h2oai` h2o Flow server
* `jpynb` Anaconda Python with additional packages: h2o, xgboost, lightgbm
* `pyspnb` Ancaonda Python with stand-alone Spark
* `rstudio` Rstudio Server (Community Edition)
* `tfcpu` Tensorflow with Python 3 and Jupyter Notebook (cpu)
* `tfgpu` Tensorflow with Python 3 and Jupyter Notebook (gpu)
