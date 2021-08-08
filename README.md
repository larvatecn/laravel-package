Laravel Package
---

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
