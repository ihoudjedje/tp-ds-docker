FROM mysql/mysql-server:5.6

MAINTAINER ilyes houdjedje <houdjedje.ilyes@gmail.com>

ENV MYSQL_DATABASE=<test> \
    MYSQL_ROOT_PASSWORD=<root>

ADD my-db-schema.sql /docker-entrypoint-initdb.d

EXPOSE 3306
