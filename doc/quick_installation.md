# Quick installation

## Download dependencies

```bash
composer install
```

## Create .env file

Windows:

```bash
copy .env.example .env
```

Linux:

```bash
cp .env.example .env
```

## Generate application key

```bash
php artisan key:generate
```

## Create database

```bash
php artisan migrate
```

## Seed datas

```bash
php artisan db:seed
```

## Start application

```bash
php artisan serve
```
