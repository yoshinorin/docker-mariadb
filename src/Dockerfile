FROM mariadb:10.11.2-jammy

LABEL maintainer="yoshinorin"

RUN apt update -y \
  && apt install less vim -y \
  && apt autoremove \
  && apt clean

COPY ./config/my.cnf /etc/mysql/my.cnf