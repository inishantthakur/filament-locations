![Screenshot](https://raw.githubusercontent.com/tomatophp/filament-locations/master/arts/3x1io-tomato-locations.jpg)

# Filament Locations

[![Dependabot Updates](https://github.com/tomatophp/filament-locations/actions/workflows/dependabot/dependabot-updates/badge.svg)](https://github.com/tomatophp/filament-locations/actions/workflows/dependabot/dependabot-updates)
[![PHP Code Styling](https://github.com/tomatophp/filament-locations/actions/workflows/fix-php-code-styling.yml/badge.svg)](https://github.com/tomatophp/filament-locations/actions/workflows/fix-php-code-styling.yml)
[![Tests](https://github.com/tomatophp/filament-locations/actions/workflows/tests.yml/badge.svg)](https://github.com/tomatophp/filament-locations/actions/workflows/tests.yml)
[![Latest Stable Version](https://poser.pugx.org/tomatophp/filament-locations/version.svg)](https://packagist.org/packages/tomatophp/filament-locations)
[![License](https://poser.pugx.org/tomatophp/filament-locations/license.svg)](https://packagist.org/packages/tomatophp/filament-locations)
[![Downloads](https://poser.pugx.org/tomatophp/filament-locations/d/total.svg)](https://packagist.org/packages/tomatophp/filament-locations)

A database of countries, cities, area, languages, currenacy with json base and database base for FilamentPHP

## Screenshots

![Countires](https://raw.githubusercontent.com/tomatophp/filament-locations/master/arts/country.png)
![Edit Countires](https://raw.githubusercontent.com/tomatophp/filament-locations/master/arts/edit-country.png)
![Languages](https://raw.githubusercontent.com/tomatophp/filament-locations/master/arts/languages.png)
![Currency](https://raw.githubusercontent.com/tomatophp/filament-locations/master/arts/currency.png)
![Locaitons](https://raw.githubusercontent.com/tomatophp/filament-locations/master/arts/locations.png)


## Installation

```bash
composer require tomatophp/filament-locations
```
after install your package please run this command

```bash
php artisan filament-locations:install
```

finally reigster the plugin on `/app/Providers/Filament/AdminPanelProvider.php`

```php
->plugin(\TomatoPHP\FilamentLocations\FilamentLocationsPlugin::make())
```

## Currency Helper

```php
dollar($amount)
```

it will return the money amount with the currency symbol

## Publish Assets

you can publish config file by use this command

```bash
php artisan vendor:publish --tag="filament-locations-config"
```

you can publish views file by use this command

```bash
php artisan vendor:publish --tag="filament-locations-views"
```

you can publish languages file by use this command

```bash
php artisan vendor:publish --tag="filament-locations-lang"
```

you can publish migrations file by use this command

```bash
php artisan vendor:publish --tag="filament-locations-migrations"
```

## Other Filament Packages

Checkout our [Awesome TomatoPHP](https://github.com/tomatophp/awesome)

