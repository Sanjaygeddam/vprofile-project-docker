FROM mysql:5.7.25

ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="accounts"

ADD db.sql /docker-entrypoint-initdb.d/db.sql