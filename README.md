# docker-nginx-php-fpm
Docker: Nginx + PHP-FPM

## Build
```
$ docker build -t nginx-php .
```

## Create container
```
$ docker run --name webserver -p 8000:80 -d nginx-php
```

## Logs
```
$ docker logs -f webserver
```
