FROM jupyter/tensorflow-notebook 

MAINTAINER hoondori@gmail.com

USER root

RUN apt-get update \
    && conda install -y -c menpo opencv3=3.1.0 

USER $NB_USER

RUN pip install keras \
    && pip install gym
