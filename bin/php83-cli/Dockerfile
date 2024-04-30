# @see https://hub.docker.com/_/php

FROM php:8.3-cli

# already done in php83
# COPY --from=composer:latest /usr/bin/composer /usr/local/bin/composer

# PM (13.04.2024) making sure the executive rights are set
# @see https://www.pluralsight.com/blog/it-ops/linux-file-permissions
RUN mkdir -p /var/www/helpers
RUN chmod a=rwx /var/www/helpers
