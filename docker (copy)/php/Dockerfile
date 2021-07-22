FROM php:7.4-fpm

# Copy application files to contaier
COPY . /var/www/

# Install PDO
RUN docker-php-ext-install mysqli pdo pdo_mysql

# Set property permissions to files
RUN chown -R www-data:www-data /var/www

WORKDIR /var/www
