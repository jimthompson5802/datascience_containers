FROM continuumio/anaconda3:5.3.0

#
# Add h2o python libraries
#
# install based on http://h2o-release.s3.amazonaws.com/h2o/rel-xia/1/docs-website/h2o-docs/downloading.html#install-in-python
#
RUN apt-get -y update && apt-get -y install openjdk-8-jdk &&  \
	pip install requests &&\
	pip install tabulate &&\
	pip install "colorama>=0.3.8" && \
	pip install future && \
    pip install -f http://h2o-release.s3.amazonaws.com/h2o/latest_stable_Py.html h2o


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

