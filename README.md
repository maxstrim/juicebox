# juicebox
Juicebox library for drupal juicebox module downloadable through composer
## Note : This is intender for Drupal 8 composer install.

## Installation

In composer.json under repositories add the following:
```json

    {
      "type": "package",
      "package": {
        "name": "maxstrim/juicebox",
        "version": "1.5.1",
        "type": "drupal-library",
        "dist": {
          "url": "https://github.com/maxstrim/juicebox/archive/1.5.1.zip",
          "type": "zip"
        },
        "require": {
          "composer/installers": "^1.2.0"
        }
      }
    }
```

