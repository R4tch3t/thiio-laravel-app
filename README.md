<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Enviroment setup:

APP_NAME=Laravel

APP_ENV=local

APP_KEY=base64:dGjuBUvoq/wjzyaKMrB2qlfLPONhOH9HSd7v2MmYE8o=

APP_DEBUG=true

APP_TIMEZONE=UTC

APP_URL=http://localhost

APP_LOCALE=en

APP_FALLBACK_LOCALE=en

APP_FAKER_LOCALE=en_US

APP_MAINTENANCE_DRIVER=file

APP_MAINTENANCE_STORE=database

BCRYPT_ROUNDS=12

LOG_CHANNEL=stack

LOG_STACK=single

LOG_DEPRECATIONS_CHANNEL=null

LOG_LEVEL=debug

DB_CONNECTION=sqlite

#DB_HOST=127.0.0.1

#DB_PORT=3306

#DB_DATABASE=laravel

#DB_USERNAME=root

#DB_PASSWORD=

SESSION_DRIVER=database

SESSION_LIFETIME=120

SESSION_ENCRYPT=false

SESSION_PATH=/

SESSION_DOMAIN=null

BROADCAST_CONNECTION=log

FILESYSTEM_DISK=local

QUEUE_CONNECTION=database

CACHE_STORE=database

CACHE_PREFIX=

MEMCACHED_HOST=127.0.0.1

REDIS_CLIENT=phpredis

REDIS_HOST=127.0.0.1

REDIS_PASSWORD=null

REDIS_PORT=6379

MAIL_MAILER=log

MAIL_HOST=127.0.0.1

MAIL_PORT=2525

MAIL_USERNAME=null

MAIL_PASSWORD=null

MAIL_ENCRYPTION=null

MAIL_FROM_ADDRESS="hello@example.com"

MAIL_FROM_NAME="${APP_NAME}"

AWS_ACCESS_KEY_ID=

AWS_SECRET_ACCESS_KEY=

AWS_DEFAULT_REGION=us-east-1

AWS_BUCKET=

AWS_USE_PATH_STYLE_ENDPOINT=false

VITE_APP_NAME="${APP_NAME}"

#Conection to MySql needed for this project

DB_CONNECTION=mysql

DB_HOST=mysql

DB_PORT=3306

DB_DATABASE=thiio_DB

DB_USERNAME=root

DB_PASSWORD=secret_thiio

## Steps for run the Laravel App
You need have previously installed PHP, Composer and Docker in terminal run the next's commands:

1. run ```composer install``` for install all plugins neededs 
2. run ```docker-compose build app``` for build app with docker-compose
3. run ```docker-compose up -d``` for upload and run the app dockerized 
4. run ```docker exec thiio_laravel_app php artisan migrate --seed``` to migrate DB at MySQL

Go to http://localhost for test the app