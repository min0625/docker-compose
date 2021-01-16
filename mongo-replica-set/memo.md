# mongo-replica-set

## setup
```sh

echo "
127.0.0.1 mongo1
127.0.0.1 mongo2
127.0.0.1 mongo3" >> /etc/hosts

```

## connection settings
URI=mongodb://mongo1:27017,mongo2:27027,mongo3:27037/?replicaSet=rs0
