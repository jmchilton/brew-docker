# Home brew + Java
#

FROM ubuntu:14.04
MAINTAINER John Chilton <jmchilton@gmail.com>

RUN apt-get -y update
RUN apt-get -y install build-essential curl git m4 ruby texinfo libbz2-dev libcurl4-openssl-dev libexpat-dev libncurses-dev zlib1g-dev
RUN apt-get -y install wget

RUN adduser --disabled-password --home=/bioinf --gecos "" bioinf

RUN su bioinf -c 'ruby -e "$(wget -O- https://raw.github.com/Homebrew/linuxbrew/go/install)"'
