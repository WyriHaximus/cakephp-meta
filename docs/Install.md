# Installation

You can install this plugin into your CakePHP application using [composer](http://getcomposer.org).
The recommended way to install composer packages is:

```
composer require dereuromark/cakephp-meta:dev-master
```

or manually via

```
"require": {
	"dereuromark/cakephp-meta": "dev-master"
}
```
and

	composer update

Details @ https://packagist.org/packages/dereuromark/cakephp-meta

This will load the plugin (within your boostrap file):
```php
Plugin::load('Meta');
```
or
```php
Plugin::loadAll(...);
```
