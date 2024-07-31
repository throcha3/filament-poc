FROM phpdockerio/php:8.3-fpm
WORKDIR "/application"

RUN apt-get update \
    && apt-get -y --no-install-recommends install \
        php8.3-bcmath \
        php8.3-bz2 \
        php8.3-http \
        php8.3-imap \
        php8.3-intl \
        php8.3-mcrypt \
        php8.3-mysql \
        php8.3-oauth \
        php8.3-odbc \
        php8.3-raphf \
        php8.3-redis \
        php8.3-uuid \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/* /usr/share/doc/*
