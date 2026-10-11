FROM php:8.5-fpm-alpine

RUN cp "${PHP_INI_DIR}/php.ini-development" "${PHP_INI_DIR}/php.ini"

RUN apk add --no-cache -- \
	php84-pdo_mysql \
    && docker-php-ext-install \
    	pdo_mysql
