FROM wordpress:php7.1

RUN apt-get update && apt-get install -yqq git-all zlib1g-dev
RUN docker-php-ext-install zip

RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/bin/ --filename=composer