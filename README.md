# FilamentPHP Boilerplate

A ready-to-use Laravel boilerplate with FilamentPHP admin panel pre-installed and configured.

## Quick Start

To get started with FilamentPHP, simply clone this boilerplate repository:

```bash
git clone https://github.com/kristiansnts/filamentphp-boilerplate.git
cd filamentphp-boilerplate
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan make:filament-user
php artisan serve
```

## Features

- Laravel framework with FilamentPHP admin panel
- Pre-configured authentication and user management
- Ready-to-use admin dashboard
- Optimized for rapid development

## About FilamentPHP

FilamentPHP is a collection of tools for rapidly building beautiful TALL stack interfaces, designed for humans. It provides:

- Modern admin panel interface
- Form builder and table components
- User-friendly navigation and layouts
- Extensible plugin system

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Resources

- [Laravel Documentation](https://laravel.com/docs)
- [FilamentPHP Documentation](https://filamentphp.com/docs)
- [Laravel Bootcamp](https://bootcamp.laravel.com)
- [Laracasts](https://laracasts.com)

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the [Laravel Partners program](https://partners.laravel.com).

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
