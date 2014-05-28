# Wordpress Skeleton

A skeleton for creating WordPress applications

## Installation

1. Download [Composer](http://getcomposer.org/doc/00-intro.md) or update `composer self-update`.
2. Run `php composer.phar create-project josh-taylor/wordpress [dir]`

## Configuration

You will need to copy the `wp-config.php` file from the `wp` directory that was created to the root of your project.

## Plugins

Plugins can be installed using wpackagist and then adding to the `composer.json` file.

E.g:

```
...
"require": {
  "wpackagist-plugin/woocommerce": "2.1.9"
}
...
```

## Credits

Thanks to Roots for creating this awesome [blog post](http://roots.io/using-composer-with-wordpress/) on using composer with WordPress.

