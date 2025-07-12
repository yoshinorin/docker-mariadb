FROM mariadb:11.4.5-noble

LABEL maintainer="yoshinorin"

RUN apt update -y \
  && apt upgrade -y \
  && apt install --no-install-recommends less vim -y \
  && apt autoremove -y \
  && apt clean \
  && rm -rf /var/lib/apt/lists/*

COPY ./config/my.cnf /etc/mysql/my.cnf