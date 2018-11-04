# Data Science Software Stack Docker Prototype

Docker images providing the following data science software stacks for peronsal use:
* Anaconda Python with Jupyter Notebook
* Rstudio Server 
* Apache Spark (Stand-alone)
* Tensorflow (cpu and gpu versions)
* h2o
* xgboost
* lightgbm

System Requirements:
* MacOS
* [Docker for Mac](https://store.docker.com/editions/community/docker-ce-desktop-mac) 18.06.1 ce (requires kubernetes enabled)
* Chrome Browser

Directories:
* `bin` scripts to start and stop containers
* `h2oai` h2o Flow server
* `jpynb` Anaconda Python with additional packages: h2o, xgboost, lightgbm
* `pyspnb` Ancaonda Python with stand-alone Spark
* `rstudio` Rstudio Server (open source)
* `tfcpu` Tensorflow with Jupyter Notebook (cpu)
* `tfgpu` Tensorflow with Jupyter Notebook (gpu)
