# Vitamin API

Laravel API framework to be consumed by Vitamin (Vue framework).

## Stack

- Laravel 9
- Laravel Sail
- PHP 8.1
- MySQL 8

## Install

```shell
docker run --rm --interactive --tty -v $(pwd):/app composer install
```

## Start Development Server

```shell
sail up -d
```

## Run Database Migrations

```shell
sail php artisan migrate
```
