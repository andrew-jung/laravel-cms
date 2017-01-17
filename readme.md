# Laravel PHP Framework

## Official Documentation
Documentation for the framework can be found on the [Laravel website](http://laravel.com/docs).

## License
The Laravel framework is open-sourced software licensed under the [MIT license].

## Project Sypnosis
A content management system built for my web development final.  Features a fully working register/login, permissions, lost password links.  On the front end, as a base registered user, you may submit articles to pages and edit/delete your own.  With upgraded permissions, you are able to create/update/delete other articles, pages, content areas, enable css templates.  Admins have full control over aforementioned as well as access to creating/deleting users.

## Pre-requisites
* PHP
* Laravel
* Composer

## Installing
```sh
$ Clone repository
$ Edit/create .env
$ Create a database file (.sqlite used for this project), edit config/database.php to reflect your choice
$ composer install
$ php artisan migrate
```

## Testing
> Testing was done with user actions, database seeded with fake information to imitate real clients
> Built for localhost, probably compatible with live system (Apache, etc)
