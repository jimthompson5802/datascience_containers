FROM continuumio/anaconda3:latest

RUN apt-get update && apt-get -y install build-essential
# #
# #  install xgboost and lightgbm and hyperopt
# #
# #  https://anaconda.org/conda-forge/xgboost
# #  https://anaconda.org/conda-forge/lightgbm
# #
RUN conda install -c conda-forge xgboost lightgbm hyperopt
RUN conda install pydot pyarrow
RUN pip install shap

# specify run-time user
# make uid/gid match ec2-user on AWS
# on MacOS docker mask uid/gid in and out of container
RUN groupadd -g 500 ds_user && \
    useradd -u 500 -g 500 ds_user && \
    mkdir -p /home/ds_user && \
    chown ds_user:ds_user /home/ds_user && \
    mkdir -p /opt/project&& \
    chown ds_user:ds_user /opt/project

# set user
USER ds_user

