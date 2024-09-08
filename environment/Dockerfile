FROM php:8.3-apache

# Install necessary PHP extensions and enable Apache modules
RUN apt-get update && apt-get install -y \
    && docker-php-ext-install mysqli pdo_mysql \
    && a2enmod rewrite \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*

# Copy custom php.ini configuration
COPY ./php.ini /usr/local/etc/php/

# Set the working directory
WORKDIR /var/www/html