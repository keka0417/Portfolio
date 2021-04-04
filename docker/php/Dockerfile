FROM php:7.4-fpm-alpine

#composer install
COPY --from=composer:2.0 /usr/bin/composer /usr/bin/composer

# mysql接続に必要なモジュールインストール
RUN docker-php-ext-install pdo pdo_mysql
