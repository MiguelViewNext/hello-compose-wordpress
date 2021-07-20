# Stack de docker-compose para WordPress

Para lanzar este stack crear un fichero `.env`

```
ROOT_PASSWORD=<password para root de mysql>
WORDPRESS_PASS=<password para wordpress>
MYSQL_PASS=<password para mariadb>
USER_NAME=<username para wordpress y mariadb>
```

Despues de esto lanzar con `docker-compose up -d`
