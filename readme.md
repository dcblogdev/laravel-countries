[![Latest Version on Packagist](https://img.shields.io/packagist/v/dcblogdev/laravel-countries.svg?style=flat-square)](https://packagist.org/packages/dcblogdev/laravel-countries)
[![Total Downloads](https://img.shields.io/packagist/dt/dcblogdev/laravel-countries.svg?style=flat-square)](https://packagist.org/packages/dcblogdev/laravel-countries)

![Logo](https://repository-images.githubusercontent.com/170597804/0b789d80-49be-11eb-9cdc-702ab39dfb88)

A Laravel countries list package

## Installation

Via Composer

```
composer require dcblogdev/laravel-countries
```

In Laravel 5.5 the service provider will automatically get registered. In older versions of the framework just add the service provider in config/app.php file:

```php
'providers' => [
    // ...
    Dcblogdev\Countries\CountriesServiceProvider::class,
];
```

## Usage

In a controller import the class:

```php
use Dcblogdev\Countries\Facades\Countries;
```

In a view or closure call the facade:

This will return an object of countries

```php
Countries::all();
```
 
## Change log

Please see the [changelog](changelog.md) for more information on what has changed recently.


## Contributing

Contributions are welcome and will be fully credited.

Contributions are accepted via Pull Requests on [Github](https://github.com/dcblogdev/laravel-countries).

## Pull Requests

- **Document any change in behaviour** - Make sure the `readme.md` and any other relevant documentation are kept up-to-date.

- **Consider our release cycle** - We try to follow [SemVer v2.0.0](http://semver.org/). Randomly breaking public APIs is not an option.

- **One pull request per feature** - If you want to do more than one thing, send multiple pull requests.

## Security

If you discover any security related issues, please email dave@daveismyname.com email instead of using the issue tracker.

## License

license. Please see the [license file](license.md) for more information.
