# mongo-replica-set

## setup
```sh

echo "
127.0.0.1 mongo1
127.0.0.1 mongo2
127.0.0.1 mongo3" >> /etc/hosts

```

## cmd
```sh

docker-compose exec mongo1 mongo

mongo "mongodb://mongo1:27017,mongo2:27027,mongo3:27037/?replicaSet=rs0"

mongosh "mongodb://mongo1:27017,mongo2:27027,mongo3:27037/?replicaSet=rs0"

```

## mongo shell
```js

// show using db
db;

show dbs;

use xxxDB;

show collections;

// check replica set status
rs.status();

```
