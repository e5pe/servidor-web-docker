FROM php:7.4-apache
RUN apt update && apt upgrade -y
RUN docker-php-ext-install mysqli
# install node js 12.x
RUN curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
RUN apt-get install -y nodejs
EXPOSE 80
