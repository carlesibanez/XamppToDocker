# Base image with build tools
FROM php:5.6.15-apache

# Install required PHP extensions
RUN docker-php-ext-install mysqli && docker-php-ext-enable mysqli

# Being tested
COPY php.ini /var/www/html/php.ini
