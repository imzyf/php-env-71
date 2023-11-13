# PHPDOCK

## Env

```env
DATA_PATH_HOST=~/.phpdock74/data
COMPOSE_PROJECT_NAME=phpdock74
PHP_VERSION=7.4

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
