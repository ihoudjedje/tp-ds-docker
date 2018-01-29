FROM nimmis/apache-php5

MAINTAINER ilyes houdjedje <houdjedje.ilyes@gmail.com>

RUN apt-get update && \
    apt-get upgrade && \
    apt-get -y install git

RUN mkdir -p var/www/html && \
    git clone https://github.com/ilyeSudo/crud-php-simple.git var/www/html

EXPOSE 80
