# Connect to container

```sh
docker-compose exec mongodb-mongodb-1 bash
```

# Connect with mongosh

```sh
mongosh "mongodb://root:root123@localhost:27017/?authMechanism=DEFAULT&tls=false"
mongosh "mongodb+srv://hmaluy:192095@cluster0.zyrbe3x.mongodb.net/"
```

```sh
show dbs
show collections
```

```sh
use("platzi_store")
db.products.find()
```

