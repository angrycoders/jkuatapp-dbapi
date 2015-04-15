#jkuatapp/dbapi

JKUAT App database interface

## Install

Via Composer

```
$ composer require angrycoders/db
```

Get master branch update (has the oldest code)

```
require "angr/dbapi": "dev-master"
```

Get develop branch update (has the latest code)

```
require "jkuatapp/dbapi": "dev-develop"
```

Get for a specific version

```
require "jkuatapp/dbapi": "1.0.0"
```

## Usage

```php
require_once "../vendor/autoload.php";

use AngryCoders\Db\Db;

$host = "localhost";
$username = "felix";
$password = "felix2010"; //Required
$database = "jkuatapp"; //Creates the db for you

//After initialising the db object the databases and all its tables are created automatically
$db = new DbJkuatApp($host, $username, $password, $database);
```

## Testing

``` bash
$ phpunit
```

## Contributing

Please see CONTRIBUTING.md for details.

## Security

If you discover any security related issues, please email keysindicet@gmail.com instead of using the issue tracker.

## Credits

Magani Felix


## License

The MIT License (MIT). Please see LICENSE.md for more information.
