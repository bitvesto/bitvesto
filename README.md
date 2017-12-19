# BITVESTO 
## Welcome to Bitvesto Documentation

Every request to endpoints must be accompanied with request headers. See below reference.

These are the list: 
`Accept: application/json`
`Content-Type: application/json`
`Authorization: Bearer your-complex-token-here`

### Login [POST /login]

+ Request Body
```json
{
  "username": "yourusername",
  "password": "yourcomplexpassword"
}
```

+ Response 200
```json
{
  "access_token": "this-is-complex-string"
}
```
