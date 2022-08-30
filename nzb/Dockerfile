FROM ubuntu:20.04
WORKDIR /init_config
COPY nzb/nzb_config nzb

RUN apt update && apt install -y rsync

WORKDIR /