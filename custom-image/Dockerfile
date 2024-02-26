FROM wordpress:6.4.3-php8.1-apache

RUN apt-get update && \
		apt-get install -y iputils-ping && \
		apt-get install -y default-mysql-client && \
		apt-get install -y vim

ADD wp-config.php /var/www/html/wp-config.php
RUN chown -R www-data:www-data /var/www/html/wp-config.php
