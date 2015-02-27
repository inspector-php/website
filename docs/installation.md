# Installation

You usually add inspector to your project's composer.json file (in the `require-dev` section),
just like phpunit, phpspec, etc.

## Adding inspector through composer:

It is recommended to use composer to install Inspector:
```
composer require inspector/inspector "~1.0"
```
Alternatively you can add the following to the require section in your composer.json manually:
```
"inspector/inspector": "~1.0"
```
Run `composer update` afterwards to install your new project dependency.
