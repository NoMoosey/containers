FROM ubuntu:20.04
WORKDIR /init_config
COPY --chown=abc:abc sonarr/sonarr_config sonarr

RUN apt update && apt install -y rsync

WORKDIR /