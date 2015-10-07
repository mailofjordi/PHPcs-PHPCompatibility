About
-----
This project is a fork of [squizlabs/PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer).

It aloww us to build `phpcs.phar` with [wimg/PHPCompatibility](https://github.com/wimg/PHPCompatibility).

It's useful if you dont want to use PEAR nor COMPOSER to install `phpcs` but you want to use the [wimg/PHPCompatibility](https://github.com/wimg/PHPCompatibility) standard.

Requirements
------------

PHP\_CodeSniffer requires PHP version 5.1.2 or greater, although individual sniffs may have additional requirements such as external applications and scripts. See the [Configuration Options manual page](https://github.com/squizlabs/PHP_CodeSniffer/wiki/Configuration-Options) for a list of these requirements.

The SVN pre-commit hook requires PHP version 5.2.4 or greater due to its use of the vertical whitespace character.

Installation
------------

You can download the PHPcs-PHPCompatibility source and build a `phpcs.phar` and `phpcbf.phar`:

    git clone git://github.com/mailofjordi/PHPcs-PHPCompatibility.git
    cd PHPcs-PHPCompatibility
    php scripts/build-phar.php phpcs.phar
    php phpcs.phar --standard=PHPCompatibility --runtime-set testVersion 5.6

Documentation
-------------

The documentation for PHP\_CodeSniffer is available on the [Github wiki](https://github.com/squizlabs/PHP_CodeSniffer/wiki).

Information about upcoming features and releases is available on the [Squiz Labs blog](http://www.squizlabs.com/php-codesniffer).

Issues
------

Bug reports and feature requests can be submitted on the [Github Issue Tracker](https://github.com/squizlabs/PHP_CodeSniffer/issues) or the [PEAR bug tracker](http://pear.php.net/package/PHP_CodeSniffer/bugs).

Contributing
-------------

See [CONTRIBUTING.md](CONTRIBUTING.md) for information.
