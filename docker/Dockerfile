FROM debian:stretch
LABEL maintainer="autx Developers <dev@autradex.systems>"
LABEL description="Dockerised autxCore, built from Travis"

RUN apt-get update && apt-get -y upgrade && apt-get clean && rm -fr /var/cache/apt/*

COPY bin/* /usr/bin/
