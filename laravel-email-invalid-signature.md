# Laravel Email Varification Invalid Signature Issue


> Simply add * in $proxies attribute value in Laravel TrustProxies Middleware 

The ``TrustProxies.php`` file located in this ``App\Http\Middleware``
```php
protected $proxies = '*';
protected $headers = Request::HEADER_X_FORWARDED_ALL;

```


See more [here](https://laracasts.com/discuss/channels/laravel/hitting-403-page-when-clicking-verify-link-in-email-using-new-laravel-verification-57)
