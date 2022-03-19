Laravel Package
---

<p align="center">
    <a href="https://github.com/larvatecn/laravel-package/actions/workflows/Linter.yml"><img src="https://github.com/larvatecn/laravel-package/actions/workflows/Linter.yml/badge.svg" alt="Linter Status"></a>
    <a href="https://github.com/larvatecn/laravel-package/actions/workflows/Tester.yml"><img src="https://github.com/larvatecn/laravel-package/actions/workflows/Tester.yml/badge.svg" alt="Tester Status"></a>
    <a href="https://packagist.org/packages/larva/laravel-package"><img src="https://poser.pugx.org/larva/laravel-package/v/stable" alt="Stable Version"></a>
    <a href="https://packagist.org/packages/larva/laravel-package"><img src="https://poser.pugx.org/larva/laravel-package/downloads" alt="Total Downloads"></a>
    <a href="https://packagist.org/packages/larva/laravel-package"><img src="https://poser.pugx.org/larva/laravel-package/license" alt="License"></a>
</p>

Laravel package template.

## Installing

```shell
$ composer require larva/laravel-package -vvv
```

### Migrations

This step is also optional, if you want to custom the pivot table, you can publish the migration files:

```php
$ php artisan vendor:publish --provider="Larva\\LaravelPackage\\PackageServiceProvider" --tag=migrations
```

## Usage

TODO

### Events

| **Event**                                       | **Description**                             |
| ----------------------------------------------- | ------------------------------------------- |
| `Larva\LaravelPackage\Events\SampleEvent`    | Sample description.                         |

## License

MIT
