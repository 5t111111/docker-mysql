# docker-mysql

Official MySQL image with UTF8 character set and `ja_JP.UTF-8 UTF-8` locale.

__/etc/mysql/conf.d/charset.cnf__

```
[mysqld]
character-set-server=utf8mb4
collation-server=utf8mb4_general_ci
[client]
default-character-set=utf8mb4
```
