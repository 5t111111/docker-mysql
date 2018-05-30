# docker-mysql

Official MySQL image with UTF8 character set.

__/etc/mysql/conf.d/charset.cnf__

```
[mysqld]
character-set-server=utf8mb4
collation-server=utf8mb4_general_ci
[client]
default-character-set=utf8mb4
```
