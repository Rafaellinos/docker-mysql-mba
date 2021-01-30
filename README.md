# docker-mysql-mba

```console
foo@bar:~$ docker run -d -e MYSQL_ALLOW_EMPTY_PASSWORD=yes -p 3306:3306 --name mba_mysql mysql:5.6
foo@bar:~$ mysql --host=127.0.0.1 --port=3306 -u root
```
