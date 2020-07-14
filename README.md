# Laravel-Mitnick

![Packagist Downloads](https://img.shields.io/packagist/dt/mitnick/laravel-security?style=for-the-badge)
![GitHub repo size](https://img.shields.io/github/repo-size/getspooky/Laravel-Mitnick?style=for-the-badge)
![GitHub](https://img.shields.io/github/license/getspooky/Laravel-Mitnick?style=for-the-badge)

Laravel-Mitnick helps you secure your Laravel apps by setting various HTTP headers. It's not a silver bullet, but it can help!

## Quick start

First, You can install the package via composer: 
```sh
composer require mitnick/laravel-security 
```

## Documentation

For installation instructions, in-depth usage and deployment details, please take a look at the official [documentation](https://getspooky.github.io/Laravel-Mitnick/).

## Requirements

Laravel-Mitnick  has a few requirements you should be aware of before installing :

* Composer
* Laravel Framework 5.4+

## Solved : Security vulnerability

| Vulnerability | Middleware Class  |   Included
| ------- | --- | --- |
| Cache Control Attack | Mitnick\Laravel\Security\cache::class |  ✔
| Cross-Origin Resource Sharing (CORS) |  Mitnick\Laravel\Security\cors::class |✔
| X-Permitted-Cross-Domain-Policies | Mitnick\Laravel\Security\crossDomain::class | ✔
| DNS Prefetch Control | Mitnick\Laravel\Security\dns::class |✔
| Click Jacking Attack | Mitnick\Laravel\Security\frameGuard::class |✔
| Strict-Transport-Security | Mitnick\Laravel\Security\hsts::class |✔
| Mime Sniffing Attack | Mitnick\Laravel\Security\noSniff::class |✔
| X-Powered-By Attack  | Mitnick\Laravel\Security\xPoweredBy::class | ✔
| XSS Attack | Mitnick\Laravel\Security\xss::class |✔


## Contributing 

Whether you're helping us fix bugs, improve the docs, or spread the word, we'd love to have you as part of the `Laravel-Mitnick` community! 💪💜  See CONTRIBUTING.md for more information on what we're looking for and how to get started.

## License

The Laravel-Mitnick package is open-source software licensed under the [MIT license](https://opensource.org/licenses/MIT).
