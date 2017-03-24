[![Travis CI](https://travis-ci.org/PayU/card-info-v2.svg)](https://travis-ci.org/PayU/card-info-v2) [![Latest Stable Version](https://poser.pugx.org/payu/card-info-v2/v/stable.svg)](https://packagist.org/packages/payu/card-info-v2) [![Total Downloads](https://poser.pugx.org/payu/card-info-v2/downloads.svg)](https://packagist.org/packages/payu/card-info-v2) [![License](https://poser.pugx.org/payu/card-info-v2/license.svg)](https://packagist.org/packages/payu/card-info-v2)

## Prerequisites

 * PHP 5.3 and above
 * curl extension with support for OpenSSL
 * PHPUnit 4.2.0 for running test suite (Optional)
 * Composer (Optional)

## Composer

You can install the library via [Composer](http://getcomposer.org/). Add this to your composer.json:

    {
      "require": {
        "payu/card-info-v2": "1.*"
      }
    }

Then install via:

    composer install

To use the library, include Composer's [autoload](https://getcomposer.org/doc/00-intro.md#autoloading]):

    require_once('vendor/autoload.php');

## Manual Installation

Obtain the latest version of the PayU Card Info V2 Client Library with:

    git clone https://github.com/PayU/card-info-v2.git

To use the Library, add the following to your PHP script:

    require_once __DIR__ . '/path/to/card-info-v2/src/init.php';

## Getting Started

You can find usage examples in the examples directory:

* cardExample.php - Minimal requirements for getting card info based on a card number
* tokenExample.php - Minimal requirements for getting card info based on a card token