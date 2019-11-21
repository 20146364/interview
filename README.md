# Xvolve Interview Project 1

This project requires the following:
- [Composer](https://getcomposer.org/)
- PHP 7.1.x

### Getting started:

#### Clone this repo:
```
$ git clone https://github.com/edward-sakamoto/interview-project-1.git
```

#### Install dependencies:
```
$ composer install
```

#### Setup env:
> DB credentials already setup in .env.example and .env.testing
```
$ cp .env .env.example
```

#### Generate app key:
```
$ composer run post-create-project-cmd
```

#### Run local server:
```
$ php artisan serve
```

#### Run unit tests:
```
$ phpunit
```
