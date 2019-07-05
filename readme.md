<p align="center">
<img width="250" height="250" src="https://drive.google.com/uc?id=1MnlGAUOjXefa07GZU3yenF03G3re8Idu">
</p>

<p align="center">
	<a href="">
		<img src="https://img.shields.io/badge/build-passing-green.svg" title="Stable Release">
	</a>
	<a href="">
		<img src="https://img.shields.io/badge/version-1.0.0-yellow.svg" title="Version">
	</a>
<a href="">
    	<img src="https://img.shields.io/badge/license-MIT-blue.svg" title="MIT License">
    </a>
</p>

## Why Laravel-Mitnick

Laravel-Mitnick helps you secure your Laravel apps by setting various HTTP headers. it can help!

## Quick start

First, You can install the package via composer: 
 <pre> composer require mitnick/laravel-security </pre> 

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
  
## License

The Laravel-Mitnick package is open-source software licensed under the [MIT license](https://opensource.org/licenses/MIT).
