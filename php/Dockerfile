# FROM php:8-fpm latest
FROM php:8.2-fpm

# Install PHP extensions and dependencies
RUN apt-get update && apt-get install -y \
   libzip-dev \
   unzip \
   # Add other necessary extensions like php-mysql, php-gd, etc.
   && docker-php-ext-install pdo_mysql zip

WORKDIR /var/www/html
