FROM php:8.2-fpm

RUN docker-php-ext-install pdo pdo_mysql

RUN mkdir -p /var/www/html

COPY app /var/www/html

WORKDIR /var/www/html
