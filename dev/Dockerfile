# Imagem utilizada para desenvolvimento
FROM paliari/php7-apache:latest

RUN pecl install xdebug && \
    docker-php-ext-enable xdebug && \
    pecl clear-cache && \
    rm /usr/local/etc/php/conf.d/docker-php-ext-opcache.ini && \
    rm /usr/local/etc/php/conf.d/opcache-recommended.ini
