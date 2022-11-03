FROM mariadb:10.6.10-focal

RUN apt-get update \
  && apt-get install less vim -y \
  && apt-get autoremove \
  && apt-get autoclean

COPY ./config/my.cnf /etc/mysql/my.cnf