FROM php:7.0-fpm-alpine
RUN docker-php-ext-install pdo_mysql mysqli
RUN php -r "readfile('http://getcomposer.org/installer');" | php -- --install-dir=/usr/bin/ --filename=composer
