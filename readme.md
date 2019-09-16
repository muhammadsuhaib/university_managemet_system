Open Source University Management System
==========================================

# Description
  Easy & hassle free Open Source University Management System Web Application

# Installation and use
### OSUMS is build using Laravel 5.2
```
$ git clone https://github.com/muhammadsuhaib/university_managemet_system/edit/suhaib/readme.md
```
```
$ cd university management system
```
```
$ mv .env.example .env
```
**Change configuration in .env according your need and create Database**
```
$ composer install
```
```
$ php artisan migrate
```
```
$ php artisan db:seed
```

**Give write permission to storage and bootstrap/cache directory**

```
$ php artisan serve
```

