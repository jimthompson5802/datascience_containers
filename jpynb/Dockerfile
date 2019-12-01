FROM continuumio/anaconda3:latest

# #
# #  install xgboost and lightgbm and hyperopt
# #
# #  https://anaconda.org/conda-forge/xgboost
# #  https://anaconda.org/conda-forge/lightgbm
# #
RUN conda install -c conda-forge xgboost lightgbm hyperopt
RUN conda install pydot

# specify run-time user
# make uid/gid match ec2-user on AWS
# on MacOS docker mask uid/gid in and out of container
RUN groupadd -g 500 ds_user && \
    useradd -u 500 -g 500 ds_user && \
    mkdir -p /home/ds_user && \
    chown ds_user:ds_user /home/ds_user && \
    mkdir /my_workarea && \
    chown ds_user:ds_user /my_workarea

# set user
USER ds_user

