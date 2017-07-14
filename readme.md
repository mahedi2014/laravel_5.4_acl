https://github.com/spatie/laravel-permission
https://scotch.io/tutorials/user-authorization-in-laravel-54-with-spatie-laravel-permission

### Installation
* `git clone https://github.com/mahedi2014/laravel_5.4_acl.git

* `cd acl`

* `composer install`

* save the .env.example to .env

* update the .env file with your db credentials

* `php artisan key:generate`

composer require spatie/laravel-permission
php artisan vendor:publish --provider="Spatie\Permission\PermissionServiceProvider" --tag="migrations"
php artisan vendor:publish --provider="Spatie\Permission\PermissionServiceProvider" --tag="config"
composer require laravelcollective/html
php artisan make:auth
php artisan make:model Post -m
php artisan migrate
php artisan make:controller PostController --resource
php artisan make:controller UserController --resource
