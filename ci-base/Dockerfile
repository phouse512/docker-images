FROM ubuntu:18.04

# install python3.6 + pip,venv
RUN apt-get update && apt-get install -y software-properties-common
RUN add-apt-repository ppa:deadsnakes/ppa
RUN apt-get update && apt-get install -y python3.6 python3-pip python3-venv

# install utilities
RUN apt-get install -y vim curl git

RUN apt-get update && apt-get install -y nodejs npm

