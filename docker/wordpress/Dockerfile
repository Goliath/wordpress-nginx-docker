FROM wordpress:6.2.2-fpm

RUN docker-php-ext-install pdo pdo_mysql

ENTRYPOINT ["docker-entrypoint.sh"]
CMD ["php-fpm"]