HTTP response library for PHP
=================

[![Latest Stable Version](https://poser.pugx.org/romeOz/rock-response/v/stable.svg)](https://packagist.org/packages/romeOz/rock-response)
[![Total Downloads](https://poser.pugx.org/romeOz/rock-response/downloads.svg)](https://packagist.org/packages/romeOz/rock-response)
[![Build Status](https://travis-ci.org/romeOz/rock-response.svg?branch=master)](https://travis-ci.org/romeOz/rock-response)
[![HHVM Status](http://hhvm.h4cc.de/badge/romeoz/rock-response.svg)](http://hhvm.h4cc.de/package/romeoz/rock-response)
[![Coverage Status](https://coveralls.io/repos/romeOz/rock-response/badge.svg?branch=master)](https://coveralls.io/r/romeOz/rock-response?branch=master)
[![License](https://poser.pugx.org/romeOz/rock-response/license.svg)](https://packagist.org/packages/romeOz/rock-response)

Features
-------------------
 * Support many formatters:
    - JSON
    - XML
    - RSS
    - Sitemap
    - HTML
 * Standalone module/component for [Rock Framework](https://github.com/romeOz/rock)

Installation
-------------------

From the Command Line:

```
composer require romeoz/rock-response
```

or in your composer.json:

```json
{
 "require": {
     "romeoz/rock-response": "*"
 }
}
``` 
 
Requirements
-------------------

 * **PHP 5.4+**
 * For using `SitemapResponseFormatter` required [tackk/cartographer](https://github.com/tackk/cartographer): `composer require tackk/cartographer`
 * For using `RssResponseFormatter` required [mibe/FeedWriter](https://github.com/mibe/FeedWriter): `composer require mibe/feedwriter`

>All unbolded dependencies is optional.

License
-------------------

HTTP response is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).