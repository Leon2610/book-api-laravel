# Laravel API

This is a REST API made with Laravel 9.

### Execution through PHP and composer:

Necessary to have installed on the computer:

* PHP
* Composer
* MYSQL
* Node
* NPM
* Postman (for testing the API)

Once you have the above you can execute the commands to start the application:

git clone the project

```cd BookAPI```
 
```php artisan serve```

With the above you have the application running at http://localhost:8000

## Usage

Change the *.env.example* to *.env* and add your database info

## Routes

```
GET   /api/books
GET   /api/books/id

POST   /api/books
@body: title, description, url, year, available

PUT   /api/books/id
@body: title, description, url, year, available

DELETE  /api/books/:id
```

