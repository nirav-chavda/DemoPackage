# Demo Package

This is my first custom package for displaying Hello World using composer. 

## Installation

Use the php dependency manager [composer](https://getcomposer.org/download/) to install package.

```bash
composer require "nirav-chavda/hello-world-demo @dev"
```

## Usage


```php
    require_once __DIR__ . '/../vendor/autoload.php';

    use HelloWorld\SayHello;
```

 Add the above lines at the top of your php file and then to call it , use

```php
    SayHello::world();
```
* You can also see this at [test.php](https://github.com/nirav-chavda/DemoPackage/blob/master/test/test.php) 