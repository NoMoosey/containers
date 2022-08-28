FROM ubuntu:20.04
WORKDIR /init_config
COPY /home/circleci/project/sonarr/sonarr_config sonarr

RUN apt update && apt install -y rsync

WORKDIR /