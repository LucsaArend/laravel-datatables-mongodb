# Laravel Datatables MongoDB

## About Package
Hey,
I start the development of this package now, some things may not work very well.

I'm learning English sorry for any mistakes.

Feel free to send suggestions and improvements.

## Installation

Package is available via Composer:

```bash
"lucasarend/laravel-datatables-mongodb": "^1.0"
```
or run
```bash
composer require lucasarend/laravel-datatables-mongodb
```

### Configure
Open the config/datatables.php file and add the engines manually to the config
```php
    //Replace query by LucasArend\DataTablesMongoDB\QueryDataTable::class,
    //Original Config
    'engines'        => [
        'eloquent'   => Yajra\DataTables\EloquentDataTable::class,
        'query'      => Yajra\DataTables\QueryDataTable::class,
        'collection' => Yajra\DataTables\CollectionDataTable::class,
    ],
    //Afeter Replace Config
    'engines'        => [
        'eloquent'   => Yajra\DataTables\EloquentDataTable::class,
        'query'      => LucasArend\DataTablesMongoDB\QueryDataTable::class,
        'collection' => Yajra\DataTables\CollectionDataTable::class,
    ],
```

## Documentation
You will use the Datatable in the same way.
[Documentation](https://yajrabox.com/docs/laravel-datatables/10.0) for more information.

## License

The MIT License (MIT). Please see [License File](https://github.com/LucsaArend/foxy-http/blob/main/LICENSE) for more information.