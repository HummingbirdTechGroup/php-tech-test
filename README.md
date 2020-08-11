# PHP Tech test
Base project for the PHP technical test

## Getting started 
The recommended way is using docker and docker-compose.
The command to start the containers is:
```
docker-compose up
```
Then you can get all the third party libraries executing:
```
docker-compose exec webapp composer install
```

## Configuration
Because this project has Dotenv component is encourage to have the file:
```
.env.local
```
In this way you can keep your own personal configuration or secrets.
