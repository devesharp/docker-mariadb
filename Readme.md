
# Mariadb Multiple database

### Using

Expand Mariadb Docker[https://github.com/MariaDB/mariadb-docker] with option for multiple database:

`docker-compose.yml`
```shell
version: '3.7'
services:
  db:
    build: .
    environment:
        MARIADB_MULTIPLE_DATABASE: testing,develop
        MYSQL_ROOT_PASSWORD: 123456
```