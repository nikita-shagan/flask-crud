# Simple flask crud

Application allows to create, read and update items in MongoDB database


### Local setup:
```
docker-compose up -d
```

### Postman testing example:

##### Create item
```
POST
http://localhost:5000/items
{
    "hello": "world"
}
```

##### Read all items
```
GET
http://localhost:5000/items
```

##### Read specific item
```
GET
http://localhost:5000/items/<id>
```

##### Delete specific item
```
DELETE
http://localhost:5000/items/<id>
```
