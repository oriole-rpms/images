ARG PGVERSION=11
FROM rockylinux:8
WORKDIR /usr/src/app

COPY . .
RUN dnf install -y make && \
    make && \
    rm *

