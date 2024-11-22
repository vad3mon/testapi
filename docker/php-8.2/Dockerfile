FROM composer:latest AS composer
FROM php:8.2-fpm

RUN docker-php-ext-install pdo_mysql

# Установка композера
COPY --from=composer /usr/bin/composer /usr/bin/composer

WORKDIR /var/www/html

# Открытие портов
EXPOSE 9000

# Запуск php
CMD ["php-fpm"]
