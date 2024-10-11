## Connect to container

```
sh
    docker-compose exec mongodb bash
```

## Connect with mongosh

```

sh 
    mongosh "mongodb+srv://alexgsierra22_101:Dyxu6P7G6jDnidyu@mongodb101.4ewwc.mongodb.net/?retryWrites=true&w=majority&appName=MongoDB101"

    mongosh "mongodb://localhost:27017/"
```

```

sh 
    show dbs
    show collections
```

```

sh 
    use('Platzi_store')
    db.productos.find()
```