FROM lkldocker/circleci:0.2
MAINTAINER Hajime Tazaki <thehajime@gmail.com>

RUN sudo apt-get update && \
    sudo apt-get install -y libfuse-dev libarchive-dev linux-headers-4.4.0-97-generic valgrind && \
    sudo rm -rf /var/lib/apt/lists/*
