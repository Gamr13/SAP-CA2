Main Branch

```
docker network create

docker run -d -p 3306:3306 --name mysql-docker-container -e MYSQL_ROOT_PASSWORD=my-secret-password -e MYSQL_DATABASE=myDB -e MYSQL_USER=adm1n -e MYSQL_PASSWORD=my-secret-password mysql/mysql-server:latest

docker run -d -p 8080:80 -e PMA_HOST=mySqlDB --name phpmyadmin --net mysql-network phpmyadmin:5.1-apache

```
