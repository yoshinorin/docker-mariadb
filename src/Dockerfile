# docker buildx imagetools inspect mariadb:11.8.8-noble
FROM mariadb:11.8.8-noble@sha256:be1ef4fe5f14589325c08a41c76334097ce66c86264b75e1d28342c742782a61

LABEL maintainer="yoshinorin"

RUN apt update -y \
  && apt upgrade -y \
  && apt install --no-install-recommends less vim -y \
  && apt autoremove -y \
  && apt clean \
  && rm -rf /var/lib/apt/lists/*

COPY ./config/my.cnf /etc/mysql/my.cnf