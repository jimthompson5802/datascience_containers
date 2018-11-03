# Data Science Software Stack Docker Prototype

Personal docker containers that provide data science software.  Containers 
support the following software stacks:
* Anaconda Python with Jupyter Notebook
* Rstudio Server 
* Apache Spark (Stand-alone)
* Tensorflow
* h20

System Requirements:
* MacOS
* [Docker for Mac](https://store.docker.com/editions/community/docker-ce-desktop-mac) 18.06.1 ce (requires kubernetes enabled)
* Chrome Browser

Directories:
* `bin` scripts to start and stop containers
* `h2o` h2o server
* `jpynb` Anaconda Python
* `pyspnb` Ancaonda Python with stand-alone Spark
* `rstudio` Rstudio Server (open source)
* `tfcpu` Anaconda Python with Tensorflow (cpu-only)
