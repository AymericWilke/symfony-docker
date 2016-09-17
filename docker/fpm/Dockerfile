FROM php:7.0.9-fpm

RUN apt-get update && apt-get install -y \
        libfreetype6-dev \
        libjpeg62-turbo-dev \
        libmcrypt-dev \
        libpng12-dev \
        libicu-dev \
    && docker-php-ext-install -j5 gd mbstring mysqli pdo pdo_mysql shmop bcmath intl
