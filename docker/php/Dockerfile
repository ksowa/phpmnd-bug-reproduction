FROM php:7.4-cli

RUN apt-get update
RUN apt-get install -y unzip libzip-dev
RUN pecl install zip

RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer

WORKDIR /var/www
