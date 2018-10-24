# Data Science Software Stack Docker Prototype

Personal docker containers that provide data science software.  Containers 
support the following software stacks:
* Aanconda Python with Jupyter Notebook
* Rstudio Server 
* Apache Spark (Stand-alone)

System Requirements:
* MacOS
* Docker 18.06.1 ce
* Chrome Browser

Directories:
* `bin` scripts to start and stop containers
* `jpynb` Anaconda Python with Jupyter notebook
* `pyspnb` Ancaonda Python with Jupyter notebook with stand-alone Spark
* `rstudio` Rstudio Server (open source)
* `dscntr` Container that combines Anaconda Python and RStudio Server


Limitations:
* Rstudio authentication dependent of static password stored in rstudio.env
* Slow performance during conda create if directory for conda environment is outside of container