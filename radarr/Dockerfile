FROM ubuntu:20.04
WORKDIR /init_config
COPY radarr/radarr_config radarr

RUN apt update && apt install -y rsync

WORKDIR /