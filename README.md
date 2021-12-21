# WordPress Composer Site

This is a WordPress site setup using Composer based on the [SpinupWP Composer Site](https://github.com/deliciousbrains/spinupwp-composer-site) for hosting with [SpinupWP](https://spinupwp.com/).

## Requirements

* PHP >= 7.3
* Composer - [Install](https://getcomposer.org/doc/00-intro.md#installation-linux-unix-osx)

## Installation

1. Create a new repository from this template repository.
2. Add theme(s) in `public/content/themes/` as you would for a normal WordPress site
3. Add plugins(s) in `public/content/plugins/` as you would for a normal WordPress site

## Setup

Run the following commands:

```
composer install
/vendor/bin/homestead make
```

1. Set the PHP version for the `site` mapping (`php: "7.4"`) in [Homestead.yaml](/Homestead.yaml)
3. Update `/etc/hosts` with the site domain and the ip in [Homestead.yaml](/Homestead.yaml)
4. Update environment variables (ie `WP_HOME`) in the `.env` file
6. Access WordPress admin at `https://mysite.com/wp/wp-admin/`