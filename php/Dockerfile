FROM php:7.4-fpm

# install configure file
RUN cp /usr/local/etc/php/php.ini-production /usr/local/etc/php/php.ini

# settings
COPY settings/php.ini /usr/local/etc/php/conf.d/php.ini
COPY settings/www.conf /usr/local/etc/php-fpm.d/www.conf
# app sources
# COPY 

EXPOSE 8000
EXPOSE 9000
