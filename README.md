Sphinx Search PHP Client
========================

[Sphinx] [1] is an open source full-text search engine.

This project contains a refactored Sphinx PHP client with some minor differences:

* Compatibility with [Composer] [2]
* Compliance with [PSR standards] [3]

Installation
------------

Create a `composer.json` file and run `composer install`:

    {
        "require": {
            "gitlog/sphinxphp": "dev-master"
        }
    }

Usage
-----

Refer to the official [documentation] [4].

Note: public functions have been changed to lower camelcase in accordance with PSR-1.

[1]: http://sphinxsearch.com/
[2]: http://getcomposer.org/
[3]: https://github.com/php-fig/fig-standards
[4]: http://sphinxsearch.com/docs/
