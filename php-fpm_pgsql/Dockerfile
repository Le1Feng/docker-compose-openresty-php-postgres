FROM php:fpm-alpine
RUN set -ex \
  && apk add --no-cache --virtual .build-pgsql-deps\
    postgresql-dev
RUN docker-php-ext-install pgsql pdo_pgsql