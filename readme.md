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
docker-compose up --build
```
- install composer
```bash
docker exec -it php-laravel-ecommerce composer install 
```
- 


add to your host (virtual host)

laravel-ecommerce.rf

try access on browser


### Admin Login

visit `laravel-ecommerce.rf/admin`

user/password: `adminweb@adminweb.com/password`



1. `php artisan ecommerce:install`. This will migrate the database and run any seeders necessary. See [this episode](https://www.youtube.com/watch?v=L3EbWJmmyjo&index=18&list=PLEhEHUEU3x5oPTli631ZX9cxl6cU_sDaR).
1. `npm install`
1. `npm run dev`
