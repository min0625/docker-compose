# mysql

## connection
```sh

docker-compose exec db bash

docker-compose exec db mysql --password=test

mysql -h 127.0.0.1 --password=test

# change root can login by any host
rename user root@'localhost' to root@'%';

```
