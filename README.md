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
sail artisan migrate
```

## Deployment

Make sure to update `.env` file in production:

- Update `APP_NAME`, `APP_URL` and `FRONTEND_DOMAIN`.
- Change `CORS_ALLOWED_ORIGINS` to use `https` instead of `http`.
- Use a fast and production grade `CACHE_DRIVER` and `SESSION_DRIVER`.
- Update all `MAIL_` settings.
