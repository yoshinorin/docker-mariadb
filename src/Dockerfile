# docker buildx imagetools inspect mariadb:11.8.7-noble
FROM mariadb:11.8.7-noble@sha256:78185355dd49b54dd6909072531ce8d7e06aa0eccd7aa5b23c93ebb7e34c5aaa

LABEL maintainer="yoshinorin"

RUN apt update -y \
  && apt upgrade -y \
  && apt install --no-install-recommends less vim -y \
  && apt autoremove -y \
  && apt clean \
  && rm -rf /var/lib/apt/lists/*

COPY ./config/my.cnf /etc/mysql/my.cnf