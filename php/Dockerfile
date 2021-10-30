FROM php:8.0-fpm-alpine

RUN cp /usr/local/etc/php/php.ini-production /usr/local/etc/php/php.ini
COPY settings/php.ini /usr/local/etc/php/conf.d/php.ini


COPY src /usr/share/nginx/html

