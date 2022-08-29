FROM ubuntu:20.04
WORKDIR /init_config
COPY sonarr/sonarr_config sonarr

WORKDIR /init_config/sonarr
RUN chown -R 1000:1000 *

RUN apt update && apt install -y rsync

WORKDIR /