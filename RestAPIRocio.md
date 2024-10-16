# Rest API
## Arruabarrena Rocio


### GET 

##### Requests

```
GET: http://facebook.com/users?id=2 
```
##### Response 
```

{
    "status": 200,
    "users": {
            "id": 2,
            "nombre": "Rocio",
            "apellido": "Arruabarrena",
            "email": "rocioa@gmail.com",
            
        },
    }
```

### PUT

##### Requests

```
PUT: http://facebook.com/v1/user?id=2
```
##### Response
```
{
    "status": 201,
    "users": {
        "id": 2,
       "nombre": "Rocio",
        "apellido": "Arruabarrena",
        "email": "rocioa07@gmail.com"
    }
}
```

### POST 

##### Request

```
POST https://facebook.com/login
```
```
{
    "email": "rocioa07@gmail.com",
    "password": "gatitos07"
}
```
##### Response 

```
{
"status": 100,
    "message": "Inicio de sesion exitoso",
    "user": {
        "id": 2,
        "nombre": "Rocio",
        "apellido": "Arruabarrena",
        "email": "rocioa07@gmail.com"
    },
    "token": "nmKldRfNeGpVsD2MaLsLjO"
}

```
### DELETE

##### Request

``` 
DELETE https://facebook.com/users?id=2
```
```
{
    "email": "rocioa07@gmail.com",
    "password": "gatitos07"
}
```

##### Response 
```
{
    "status": 103,
    "message": "Tu cuenta ha sido eliminada con exito"
}
```