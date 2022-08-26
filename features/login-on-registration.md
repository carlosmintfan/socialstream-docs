# Login on Registration

If a user has already registered with a particular email address, and the OAuth account they attempt to register with returns the same email, the provider will be linked to the existing user and they will be logged in.

To turn on this feature add the following to applications `socialstream.php` config file:

```php
'features' => [
    Features::loginOnRegistration(),
],
```
