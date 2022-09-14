FROM mysql:5.7

ENV MYSQL_ROOT_PASSWORD="mypass"
ENV MYSQL_DATABASE="hedgehog"
ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql


