FROM php:7.0-fpm
RUN apt-get update && apt-get upgrade -y && apt-get install curl wget vim -y
RUN docker-php-ext-install pdo_mysql mysqli mbstring;
RUN mkdir -p /run/php && chown www-data:www-data /run/php

COPY ./config/php.ini /usr/local/etc/php/php.ini
#COPY ./config/www.conf /etc/php/7.0/fpm/www.conf
#COPY ./config/www.conf /usr/local/etc/php-fpm.d/zz-www.conf


