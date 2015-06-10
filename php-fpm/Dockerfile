FROM php:fpm
# Install modules
RUN apt-get update && apt-get install -y \
    libmcrypt-dev
RUN docker-php-ext-install iconv mcrypt

CMD ["php-fpm"]


