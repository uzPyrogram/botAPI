# PHP-UTILITY

This is php utilities.

Requirements
---------

* PHP >= 7.4
* Curl extension for PHP7 must be enabled.

Download
---------

#### Using Composer

From your project directory, run:
```
composer require algol-team/library
```
or
```
php composer.phar require algol-team/library
```
Note: If you don't have Composer you can download it [HERE](https://getcomposer.org/download/).


#### Using Git

From a project directory, run:
```
git clone https://github.com/algol-team/php-utility.git
```

Installation
---------

#### Via Composer's autoloader

After downloading by using Composer, you can include Composer's autoloader:
```php
include (__DIR__ . '/vendor/autoload.php');

$Telegram = new TelegramOf('YOUR TELEGRAM TOKEN HERE');
```
License
------------

This open-source software is distributed under the MIT License. See LICENSE.md

Contributing
------------

All kinds of contributions are welcome - code, tests, documentation, bug reports, new features, etc...

* Send feedbacks.
* Submit bug reports.
* Write/Edit the documents.
* Fix bugs or add new features.
