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
      libtool \
      libtool-bin \
      mingw-w64 \
      p7zip-full \
      clang \
      llvm-dev \
      libxml2-dev \
      uuid-dev \
      libssl-dev \
      bash \
      patch \
      make \
      tar \
      xz-utils \
      bzip2 \
      gzip \
      sed \
      cpio \
      libbz2-dev \
      clang \
    && pip install awscli --upgrade \
    && apt-get clean

