# docker-alpine-lemp

LEMP stack environment.

## Current stacks:
- Alpine Linux:3.4
- Nginx:1.11.3
- PHP7.0
- PHP-FPM
- MariaDB
- memcached

## Usage

```
$ docker-compose up
```

## Environment Variables

### Nginx container
Nginx environments are set in envfiles/web_env  
- WITH_PHP_FPM
- MY_SERVER_NAME

### MariaDB container
MariaDB environments are set in envfiles/db_env.  
If you would like to change them, edit envfiles/db_env.  

This repo uses bitnami/mariadb docker image for MariaDB.
See https://hub.docker.com/r/bitnami/mariadb/ for each variables description.  

