FROM mysql:5.7.25
LABEL "Project"="reaction"
LABEL "Author"="vishal"

ENV MYSQL_ROOT_PASSWORD="mydbpassword"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql

