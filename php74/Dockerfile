FROM abudawud/php-fpm:7

RUN install-php-extensions mysqli pdo_mysql gd zip
RUN set -eux; \
    apk add --no-cache git; \
    curl -L https://getcomposer.org/composer-stable.phar -o /usr/local/bin/composer; \
    chmod uga+x /usr/local/bin/composer; \
    sync
