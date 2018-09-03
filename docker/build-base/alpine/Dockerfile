FROM alpine:3.8

LABEL maintainer="Didiet Noor <dnoor@tanibox.com>"
LABEL description="Base Image For Build Containers (Alpine Version)"

RUN BUILD_DEPS="git autoconf py2-pip automake build-base clang gperf gettext-dev xz bison flex texinfo libtool ncurses-dev wget gawk libc-dev help2man sed unzip patch"
      && apk add --update --no-cache $BUILD_DEPS \
      && pip install awscli --upgrade 

RUN adduser --disabled-password --gecos '' build

USER build
WORKDIR /home/build
