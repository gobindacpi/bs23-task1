FROM php:8-cli


RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer

WORKDIR /app
COPY . /app

RUN composer install

EXPOSE 80
CMD php artisan serve --host=0.0.0.0 --port=80

