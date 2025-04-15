# Awesome PSR-15 Middlewares [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [<img src="https://avatars1.githubusercontent.com/u/22275359?v=3&s=200" width="200" align="right" alt="MW">](https://github.com/middlewares/awesome-psr15-middlewares)

> [PSR-15 HTTP Middleware](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-15-request-handlers.md) describes a common standard for HTTP middleware components using HTTP Messages defined by [PSR-7](http://www.php-fig.org/psr/psr-7/).


Currently, PSR-15 is a PHP Standards Recommendation of the Framework Interoperability Group (_FIG_).

*Please read the [contribution guidelines](contributing.md) before contributing.*


## Contents

- [References](#references)
- [Articles](#articles)
- [Packages](#packages)

## References

- [PHP Framework Interoperability Group website](http://www.php-fig.org/)
- [PSR-15 HTTP Middleware](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-15-request-handlers.md) - The current standard.
- [psr/http-server-middleware](https://packagist.org/packages/psr/http-server-middleware) - Composer package of common interfaces for PSR-15 HTTP Middlewares.


## Articles

- [PSR-7 Objects Are Not Immutable](http://andrewcarteruk.github.io/programming/2016/05/22/psr-7-is-not-immutable.html) - Description of a serious flaw with the double-pass style of middlewares.
- [Dependency Inversion and PSR-7 Bodies](https://github.com/shadowhand/blog.shadowhand.me/blob/master/_posts/2016-05-22-dependency-inversion-and-psr-7-bodies.markdown) - Conclusion that double-pass flaws cannot be resolved without [HTTP Factories](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-17-http-factory.md).


## Packages

### PSR-7 implementations

- [laminas/laminas-diactoros](https://github.com/laminas/laminas-diactoros)
- [guzlehttp/psr7](https://github.com/guzzle/psr7)
- [slim/http](https://github.com/slimphp/Slim-Http)
- [nyholm/psr7](https://github.com/Nyholm/psr7)
- [sunrise/http-message](https://github.com/sunrise-php/http-message)
- [httpsoft/http-message](https://github.com/httpsoft/http-message)

### Dispatcher

- [relay/relay](https://github.com/relayphp/Relay.Relay) - A PSR-15 request handler for both PSR-15 *and* callable middleware; use it with any framework or container.
- [mindplay/middleman](https://github.com/mindplay-dk/middleman) - Dead simple PSR-15 / PSR-7 middleware dispatcher.
- [laminas/laminas-stratigility](https://github.com/laminas/laminas-stratigility) - Build and dispatch middleware pipelines.
- [oscarotero/middleland](https://github.com/oscarotero/middleland) - Another PSR-15 dispatcher
- [httpsoft/http-runner](https://github.com/httpsoft/http-runner) - Running PSR-7 components and building PSR-15 middleware pipelines.

### Router

- [middlewares/aura-router](https://github.com/middlewares/aura-router) - Use [Aura.Router](https://github.com/auraphp/Aura.Router/).
- [middlewares/fast-route](https://github.com/middlewares/fast-route) - Use [FastRoute](https://github.com/nikic/FastRoute).
- [sunrise/http-router](https://github.com/sunrise-php/http-router) - HTTP Router based on PSR-7 and PSR-15
- [jasny/switch-route](https://github.com/jasny/switch-route) - Generate a PHP script for faster routing
- [httpsoft/http-router](https://github.com/httpsoft/http-router) - Simple and fast HTTP request router providing PSR-7 and PSR-15.

### Security

- [middlewares/cors](https://github.com/middlewares/cors) - Manage [Cross-Origin Resource Sharing (CORS)](http://www.w3.org/TR/cors/).
- [middlewares/csp](https://github.com/middlewares/csp) - Manage [Content-Security-Policies (CSP)](https://content-security-policy.com/).
- [middlewares/honeypot](https://github.com/middlewares/honeypot) - Block spam bots.
- [middlewares/http-authentication](https://github.com/middlewares/http-authentication) - HTTP [Basic](https://en.wikipedia.org/wiki/Basic_access_authentication) and [Digest](https://en.wikipedia.org/wiki/Digest_access_authentication) access authentication.
- [middlewares/recaptcha](https://github.com/middlewares/recaptcha) - Use [Google's reCAPTCHA](https://github.com/google/recaptcha) for spam prevention.
- [ellipsephp/cookie-encryption](https://github.com/ellipsephp/cookie-encryption) - Encrypt cookies with a key

### Session

* [AuraSession](https://github.com/middlewares/aura-session) - Manage sessions using [Aura.Session](https://github.com/auraphp/Aura.Session).
* [PhpSession](https://github.com/middlewares/php-session) - Manage sessions using PHP's native session API.
* [Storageless JWT Session](https://github.com/psr7-sessions/storageless) - Manage sessions without I/O usage. 

### Development

- [middlewares/debugbar](https://github.com/middlewares/debugbar) - Inject [PHP Debug Bar](http://phpdebugbar.com/).
- [middlewares/whoops](https://github.com/middlewares/whoops) - Use [Whoops](https://github.com/filp/whoops) as error handler.


### Content

- [middlewares/encoder](https://github.com/middlewares/encoder) - Compress responses with [gzencode](http://php.net/manual/en/function.gzencode.php) or [gzdeflate](http://php.net/manual/en/function.gzdeflate.php).
- [middlewares/minifier](https://github.com/middlewares/minifier) - Minify Html, CSS and Javascript.
- [middlewares/negotiation](https://github.com/middlewares/negotiation) - Manage [content negotiations](https://tools.ietf.org/html/rfc7231#section-5.3).

### Miscellaneous

- [middlewares/geolocation](https://github.com/middlewares/geolocation) - Geolocate requests.
- [noglitchyo/dealdoh](https://github.com/noglitchyo/dealdoh) - Handle [DoH](https://tools.ietf.org/html/rfc8484) (DNS-over-HTTPS) messages.


## Links of interest

- [PSR-15 Middlewares by Middlewares Organization](https://github.com/middlewares/psr15-middlewares)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

Awesome PSR-15 Middlewares © 2016-2025 by [Middlewares Organization](https://github.com/middlewares) is licensed under [Creative Commons Attribution 4.0 International](https://creativecommons.org/publicdomain/zero/1.0/).
