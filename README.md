# has-state-laravel

[![Latest Stable Version](https://img.shields.io/github/v/release/brokeyourbike/has-state-laravel)](https://github.com/brokeyourbike/has-state-laravel/releases)
[![Total Downloads](https://poser.pugx.org/brokeyourbike/has-state-laravel/downloads)](https://packagist.org/packages/brokeyourbike/has-state-laravel)
[![License: MPL-2.0](https://img.shields.io/badge/license-MPL--2.0-purple.svg)](https://github.com/brokeyourbike/has-state-laravel/blob/main/LICENSE)

[![Maintainability](https://api.codeclimate.com/v1/badges/12a3f2c14ee47a950959/maintainability)](https://codeclimate.com/github/brokeyourbike/has-state-laravel/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/12a3f2c14ee47a950959/test_coverage)](https://codeclimate.com/github/brokeyourbike/has-state-laravel/test_coverage)
[![tests](https://github.com/brokeyourbike/has-state-laravel/actions/workflows/tests.yml/badge.svg)](https://github.com/brokeyourbike/has-state-laravel/actions/workflows/tests.yml)

Interfaces for models with state in Laravel

## Installation

```bash
composer require brokeyourbike/has-state-laravel
```

## Usage

```php
use BrokeYourBike\HasStateLaravel\HasStateLaravelInterface;
use BrokeYourBike\HasStateLaravel\HasStateLaravelTrait;

class Client implements HasStateLaravelInterface
{
    use HasStateLaravelTrait;
}
```

## License
[Mozilla Public License v2.0](https://github.com/brokeyourbike/has-state-laravel/blob/main/LICENSE)
