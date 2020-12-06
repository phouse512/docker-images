FROM ubuntu:18.04

# install python3.6 + pip,venv
RUN apt-get update && apt-get install -y software-properties-common
RUN add-apt-repository ppa:deadsnakes/ppa
RUN apt-get update && apt-get install -y python3.6 python3-pip python3-venv

# install utilities
RUN apt-get install -y vim curl git

RUN apt-get update && apt-get install -y nodejs npm

RUN apt-get install -y unzip less groff
RUN curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
RUN unzip awscliv2.zip
RUN ./aws/install

RUN npm i -g npm@6.1.0

