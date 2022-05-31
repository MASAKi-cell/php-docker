FROM php:7.4-apache

WORKDIR /var/www/html

RUN apt-get update  \
  && docker-php-ext-install pdo_mysql mysqli mbstring

EXPOSE 80
