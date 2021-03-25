## DOCKER CONTAINERS PHP APP TEST

### STACK
* PHP 7.2
* Laravel 7
* Docker
* Redis
* MariaDb

### Init
```
docker-compose up -d --build
```
### To exec inside app
```
docker-compose exec app cp .env.example .env
```

### Create test database
```
docker-compose exec db  mysql -u root -e "CREATE DATABASE test;"
```