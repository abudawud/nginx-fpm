FROM abudawud/php-fpm:5.6

RUN set -eux; \
	install-php-extensions gd pdo_mysql mysqli zip mysql calendar
RUN set -eux; \
    apk add --no-cache git; \
    curl -L https://getcomposer.org/composer-stable.phar -o /usr/local/bin/composer; \
    chmod uga+x /usr/local/bin/composer; \
    sync
