League Url
=======

[![Build Status](https://img.shields.io/travis/thephpleague/url/master.svg?style=flat-square)](https://travis-ci.org/thephpleague/url)
[![Coverage Status](https://img.shields.io/scrutinizer/coverage/g/thephpleague/url.svg?style=flat-square)](https://scrutinizer-ci.com/g/thephpleague/url/code-structure)
[![Quality Score](https://img.shields.io/scrutinizer/g/thephpleague/url.svg?style=flat-square)](https://scrutinizer-ci.com/g/thephpleague/url)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE.md)
[![Latest Version](https://img.shields.io/github/release/thephpleague/url.svg?style=flat-square)](https://github.com/thephpleague/url/releases)
[![Total Downloads](https://img.shields.io/packagist/dt/league/url.svg?style=flat-square)](https://packagist.org/packages/league/url)

The `League\Url` package provides simple and intuitive classes to create and manage Urls in PHP.

Highlights
------

- Simple API
- [RFC3986](http://tools.ietf.org/html/rfc3986) compliant
- Implements the `UriInterface` from [PSR-7][]
- Fully documented
- Framework Agnostic
- Composer ready, [PSR-2][] and [PSR-4][] compliant

Documentation
------

Full documentation can be found at [url.thephpleague.com](http://url.thephpleague.com). Contribute to this documentation in the [gh-pages](https://github.com/thephpleague/url/tree/gh-pages) branch

System Requirements
-------

You need:

- **PHP >= 5.5.0** or **HHVM >= 3.6**, but the latest stable version of PHP/HHVM is recommended
- the `mbstring` extension
- the `intl` extension

To use the library.

Install
-------

Install `League\Url` using Composer.

```
$ composer require league/url
```

Testing
-------

`League\Url` has a [PHPUnit](https://phpunit.de) test suite. To run the tests, run the following command from the project folder.

``` bash
$ phpunit
```

Contributing
-------

Contributions are welcome and will be fully credited. Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

Security
-------

If you discover any security related issues, please email nyamsprod@gmail.com instead of using the issue tracker.

Credits
-------

- [ignace nyamagana butera](https://github.com/nyamsprod)
- [All Contributors](https://github.com/thephpleague/url/contributors)

License
-------

The MIT License (MIT). Please see [License File](LICENSE) for more information.

[PSR-2]: http://www.php-fig.org/psr/psr-2/
[PSR-4]: http://www.php-fig.org/psr/psr-4/
[PSR-7]: http://www.php-fig.org/psr/psr-7/
