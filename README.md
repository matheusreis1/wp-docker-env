# wp-docker-env
Docker solution to develop wordpress plugins with Pagespeed Nginx

## How to use
- Clone this repository
- Go to the directory
- Run the command:
```
docker-compose up -d --build
```

## Possible Errors

### Error establising a database connection

- It can be the volume, change the name of MySql volume
- Or it can be the image in your machine, run
```
docker-compose pull
```
