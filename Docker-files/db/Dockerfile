FROM mysql:8.0.33
LABEL "Project"="vprofile"
LABEL "Author"="Hamada"

ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="accounts"

COPY db_backup.sql /docker-entrypoint-initdb.d/db_backup.sql

EXPOSE 3306