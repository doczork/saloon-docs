# 👋 Installation

To get started with Saloon, you will need to install it through Composer.&#x20;

```bash
composer require sammyjo20/saloon ^2.0
```

> Saloon requires PHP 8.1&#x20;

### Dependencies

Saloon requires just three dependencies.

* [Guzzle](https://github.com/guzzle/guzzle) (For The Default GuzzleSender)
* [Guzzle's Promise Library](https://github.com/guzzle/promises) (For Request Pooling & Asynchronous Requests)
* [PSR Message Library](https://github.com/php-fig/http-message) (For PSR-7 Interfaces)

### Using Laravel?

You may install the optional Saloon helper library for Laravel, which adds a config file, commands and a facade to let you easily test.

```bash
composer require sammyjo20/saloon-laravel ^2.0
```