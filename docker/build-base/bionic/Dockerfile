FROM buildpack-deps:bionic

LABEL maintainer="Didiet Noor <dnoor@tanibox.com>"
LABEL description="Base Image For Build Containers"

RUN apt-get update -qq && apt-get install -qq \
      python-pip \
      python-dev \
      build-essential \
      autoconf \
      automake \
      binutils-doc \
      bison \
      texinfo \
      flex \
      gettext \
      ncurses-dev \
      unzip \
      help2man \
      gawk \
      sed \
      libtool \
      libtool-bin \
      mingw-w64 \
      p7zip-full \
    && pip install awscli --upgrade

