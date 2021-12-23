# Skeleton for PHP packages development

This repository provides a base skeleton for PHP package development, specifically:

- PHP 8.0 docker image based on Alpine with XDebug and Composer.
- Direnv support, automatically mapping any `php` call to use this repository's docker container.
- Run tests with PHPUnit.
- Enforce PSR-12 coding styles with Php-Cs-Fixer.

## How to use this on your next project

Run `composer create-project josepostiga/skeleton-php-package --prefer-source YourPackageName`.

## Credits

- [José Postiga](https://github.com/josepostiga)
- [All Contributors](../../contributors)

## License

The MIT License (MIT).
