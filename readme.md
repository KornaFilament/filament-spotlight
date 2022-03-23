# Filament Spotlight

[![Latest Version on Packagist](https://img.shields.io/packagist/v/pxlrbt/filament-spotlight.svg?include_prereleases)](https://packagist.org/packages/pxlrbt/filament-spotlight)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg)](LICENSE.md)
![GitHub Workflow Status](https://img.shields.io/github/workflow/status/pxlrbt/filament-spotlight/Code%20Style?label=code%20style)
[![Total Downloads](https://img.shields.io/packagist/dt/pxlrbt/filament-spotlight.svg)](https://packagist.org/packages/pxlrbt/filament-spotlight)

Spotlight functionality for your Pages and Resource Pages.

## Installation

Install via Composer. This will download the package and [Wire Elements Spotlight](https://github.com/wire-elements/spotlight).

**Requires PHP > 8.0 and Filament > 2.0**

```bash
composer require pxlrbt/filament-spotlight
```

## Usage
There is no configuration needed. Just install the package.

## Todos
- [ ] PR: Page::getTitle() as public
- [ ] Add styles
- [ ] Inject scripts

## Contributing

If you want to contribute to this packages, you may want to test it in a real Filament project:

- Fork this repository to your GitHub account.
- Create a Filament app locally.
- Clone your fork in your Filament app's root directory.
- In the `/filament-spotlight` directory, create a branch for your fix, e.g. `fix/error-message`.

Install the packages in your app's `composer.json`:

```json
"require": {
    "pxlrbt/filament-spotlight": "dev-fix/error-message as main-dev",
},
"repositories": [
    {
        "type": "path",
        "url": "filament-spotlight"
    }
]
```

Now, run `composer update`.

## Credits
Dennis Koch