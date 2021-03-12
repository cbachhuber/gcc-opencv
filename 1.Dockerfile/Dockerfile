FROM ubuntu:20.04

ENV TZ=Europe/Kiev
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone

RUN apt-get update -qq && DEBIAN_FRONTENT=noninteractive apt-get install -qqy --no-install-recommends \
        build-essential \
        cmake \
        git \
        make \
        libopencv-dev \
        software-properties-common
