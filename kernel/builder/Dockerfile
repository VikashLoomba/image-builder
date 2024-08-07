FROM ubuntu:22.04

RUN apt-get update -y && \
    apt-get install -y --no-install-recommends \
        dpkg                \
        bc                  \
        bison               \
        build-essential     \
        gcc                 \
        flex                \
        git                 \
        libelf-dev          \
        libncurses-dev      \
        libssl-dev          \
        ca-certificates     \
        kmod                \
        resolvconf          \
        wireguard           \
        wget             && \
    update-alternatives --install /usr/bin/gcc gcc 
