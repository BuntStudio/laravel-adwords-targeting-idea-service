# A Laravel API Wrapper For Google AdWords.

[![Latest Version](https://img.shields.io/github/release/schulzefelix/laravel-adwords-targeting-idea-service.svg?style=flat-square)](https://github.com/schulzefelix/laravel-adwords/releases)
[![Software License][ico-license]](LICENSE.md)
[![Build Status][ico-travis]][link-travis]
[![Quality Score][ico-code-quality]][link-code-quality]
[![StyleCI](https://styleci.io/repos/92534151/shield)](https://styleci.io/repos/92534151)
[![Latest Version on Packagist][ico-version]][link-packagist]
[![Total Downloads][ico-downloads]][link-downloads]


## Install

This package can be installed through Composer.

``` bash
$ composer require schulzefelix/laravel-adwords
```

You must install this service provider.
```php
// config/app.php
'providers' => [
    ...
    SchulzeFelix\AdWords\AdWordsServiceProvider::class,
    ...
];
```

This package also comes with a facade, which provides an easy way to call the the class.

```php
// config/app.php
'aliases' => [
    ...
    'AdWords' => SchulzeFelix\AdWords\AdWordsFacade::class,
    ...
];
```


You can publish the config file of this package with this command:

``` bash
php artisan vendor:publish --provider="SchulzeFelix\AdWords\AdWordsServiceProvider"
```

## Usage

- [Introduction](#introduction)


<a name="introduction"></a>
## Introduction
Coming Soon

## Change log

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Testing

``` bash
$ vendor/bin/phpunit
```

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) and [CONDUCT](CONDUCT.md) for details.

## Security

If you discover any security related issues, please email githubissues@schulze.co instead of using the issue tracker.

## Credits

- [Felix Schulze][link-author]
- [All Contributors][link-contributors]

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[ico-version]: https://img.shields.io/packagist/v/schulzefelix/laravel-adwords-targeting-idea-service.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-travis]: https://img.shields.io/travis/schulzefelix/laravel-adwords-targeting-idea-service/master.svg?style=flat-square
[ico-scrutinizer]: https://img.shields.io/scrutinizer/coverage/g/schulzefelix/laravel-adwords-targeting-idea-service.svg?style=flat-square
[ico-code-quality]: https://img.shields.io/scrutinizer/g/schulzefelix/laravel-adwords-targeting-idea-servicesvg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/schulzefelix/laravel-adwords-targeting-idea-service.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/schulzefelix/laravel-adwords-targeting-idea-service
[link-travis]: https://travis-ci.org/schulzefelix/laravel-adwords-targeting-idea-service
[link-scrutinizer]: https://scrutinizer-ci.com/g/schulzefelix/laravel-adwords-targeting-idea-service/code-structure
[link-code-quality]: https://scrutinizer-ci.com/g/schulzefelix/laravel-adwords-targeting-idea-service
[link-downloads]: https://packagist.org/packages/schulzefelix/laravel-adwords-targeting-idea-service
[link-author]: https://github.com/schulzefelix
[link-contributors]: ../../contributors
