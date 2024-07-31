# PHPDOCK

## Introduction

My full PHP development environment for Docker.

## Quick Overview

```bash
cp .env.example .env
vi .env

# Edit .env
DATA_PATH_HOST=~/.phpdock74/data
COMPOSE_PROJECT_NAME=phpdock74
PHP_VERSION=7.4

# OR
DATA_PATH_HOST=~/.phpdock81/data
COMPOSE_PROJECT_NAME=phpdock81
PHP_VERSION=8.1
```

## Commamd

```bash
docker-compose up -d php-fpm nginx

docker-compose restart nginx

docker-compose exec workspace bash
```

## References

- [Laradock.io](https://laradock.io/)
- [imzyf/php-workspace-image](https://github.com/imzyf/php-workspace-image)
- [imzyf/php-fpm-image](https://github.com/imzyf/php-fpm-image)
