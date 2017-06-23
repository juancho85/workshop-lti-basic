FROM php:7.0-apache
RUN ["apt-get", "update"]
RUN ["apt-get", "install", "-y", "nano"]
COPY html/ /var/www/html/
RUN chown -R www-data /var/www/html/ && chmod -R 777 /var/www/html/