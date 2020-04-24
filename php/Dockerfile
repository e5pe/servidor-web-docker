ARG PHP_APACHE_VERSION
FROM php:$PHP_APACHE_VERSION
ARG NODE_VERSION_FOR_DOWNLOAD
RUN apt update && apt upgrade -y
RUN docker-php-ext-install mysqli
# update custom config of the site
RUN rm -f /etc/apache2/sites-available/000-default.conf
ADD ./000-default.conf /etc/apache2/sites-available

# install node js 12.x
# RUN curl -sL https://deb.nodesource.com/${NODE_VERSION_FOR_DOWNLOAD} | bash -
# RUN apt-get install -y nodejs

# install vue/cli
# RUN npm install -g @vue/cli
# When the app is finished
# Configuration for copying the package files will be added

EXPOSE 80
