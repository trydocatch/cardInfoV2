# [![Travis CI](https://travis-ci.org/PayU/alu-client-php.svg)](https://travis-ci.org/PayU/alu-client-php) [![Latest Stable Version](https://poser.pugx.org/payu/alu-client/v/stable.svg)](https://packagist.org/packages/payu/alu-client) [![Total Downloads](https://poser.pugx.org/payu/alu-client/downloads.svg)](https://packagist.org/packages/payu/alu-client) [![License](https://poser.pugx.org/payu/alu-client/license.svg)](https://packagist.org/packages/payu/alu-client)

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

Obtain the latest version of the PayU Automatic Live Update Client Library with:

    git clone https://github.com/PayU/card-info-v2.git

To use the Library, add the following to your PHP script:

    require_once("/path/to/card-info-v2/src/PayU/CardInfoClient.php");

## Getting Started

You can find usage examples in the examples directory:

* cardExample.php - Minimal requirements for getting card info based on a card number
* tokenExample.php - Minimal requirements for getting card info based on a card token