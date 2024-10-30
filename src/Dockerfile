FROM mariadb:11.4.3-noble

LABEL maintainer="yoshinorin"

RUN apt update -y \
  && apt upgrade -y \
  && apt install --no-install-recommends less vim -y \
  && apt autoremove \
  && apt clean

COPY ./config/my.cnf /etc/mysql/my.cnf