FROM debian:stretch
MAINTAINER Bastien Durel bastien.docker@durel.org
COPY locale.gen /etc/locale.gen
ENV LANG=fr_FR.UTF-8
RUN apt update ; DEBIAN_FRONTEND=noninteractive apt -q -y upgrade ; \
    DEBIAN_FRONTEND=noninteractive apt install -q -y \
	build-essential \
	bzip2 \
	curl \
	debhelper \
	dpkg-dev \
	g++ \
	git \
  libicu-dev \
	libexpat1-dev \
	libluabind-dev \
	libluajit-5.1-dev \
	default-libmysqlclient-dev \
	libprotobuf-dev \
	libsqlite3-dev \
	libxerces-c-dev \
	libzmq3-dev \
	locales \
	lua-json \
	make \
	openjdk-8-jdk \
	openjdk-8-jre-headless \
	pkg-config \
	wget \
    && apt-get clean
