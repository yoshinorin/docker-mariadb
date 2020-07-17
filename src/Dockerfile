FROM mariadb:10.5.4

RUN apt-get update \
  && apt-get install less vim -y \
  && apt-get autoremove \
  && apt-get autoclean

COPY ./config/my.cnf /etc/mysql/my.cnf