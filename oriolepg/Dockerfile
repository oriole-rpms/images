FROM ghcr.io/oriole-rpms/pgbuilder:latest
ARG PGVERSION=16
ENV PGVERSION=${PGVERSION}

COPY . /builder/
WORKDIR /builder
RUN ./start.sh
