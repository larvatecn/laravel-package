Laravel Package
---

[![Coding Style](https://github.com/larvatecn/laravel-package/actions/workflows/Linter.yml/badge.svg)](https://github.com/larvatecn/laravel-package/actions/workflows/Linter.yml)
[![Tester](https://github.com/larvatecn/laravel-package/actions/workflows/Tester.yml/badge.svg)](https://github.com/larvatecn/laravel-package/actions/workflows/Tester.yml)

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
