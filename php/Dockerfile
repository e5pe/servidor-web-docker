ARG PHP_APACHE_VERSION
FROM php:$PHP_APACHE_VERSION
RUN apt update && apt upgrade -y
RUN docker-php-ext-install mysqli
EXPOSE 80
