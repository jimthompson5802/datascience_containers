FROM continuumio/anaconda3:latest

RUN apt-get update && \
# install prequired modules to support install of packages
    apt-get install -y build-essential

#  install additional packages
RUN pip install rfcde

# specify run-time user
# make uid/gid match ec2-user on AWS
# on MacOS docker mask uid/gid in and out of container
RUN groupadd -g 500 ds_user && \
    useradd -u 500 -g 500 ds_user && \
    mkdir -p /home/ds_user && \
    chown ds_user:ds_user /home/ds_user && \
    mkdir -p /opt/project/meda && \
    chown ds_user:ds_user /opt/project/meda && \
    mkdir -p /opt/project/emr && \
    chown ds_user:ds_user /opt/project/emr

# set user
USER ds_user

