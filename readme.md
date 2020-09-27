![Laravel Ecommerce Example](https://user-images.githubusercontent.com/4316355/36414878-d41987b2-15f1-11e8-9f2c-6c3a68e4a14b.gif)

# Laravel Ecommerce Example

original repo : https://github.com/drehimself/laravel-ecommerce-example

## Versioning 

- Laravel : 6
- PHP : 7.3 (php7.3-fpm)
- MySQL : 5.7

## Installation

- Clone the repo and `cd` into it
- running up all container (it will take so long, depend on your connection of course)
```bash
docker-compose up --build -d
```
- install composer
```bash
docker exec -it php-laravel-ecommerce composer install 
```
- database
```bash
docker exec mysql-laravel-ecommerce sh -c 'exec mysql -uroot -p"root" < /db/laravel_ecommerce.sql'
```
- add to your host (virtual host)

`127.0.0.1 laravel-ecommerce.rf`

and, try access on browser `laravel-ecommerce.rf`

PS : stop all service using another app (like xampp)

### Admin Login

visit `laravel-ecommerce.rf/admin`

user/password: `adminweb@adminweb.com/password`
