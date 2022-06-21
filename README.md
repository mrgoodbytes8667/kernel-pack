# kernel-pack
[![Packagist Version](https://img.shields.io/packagist/v/mrgoodbytes8667/kernel-pack?logo=packagist&logoColor=FFF&style=flat)](https://packagist.org/packages/mrgoodbytes8667/kernel-pack)
[![PHP from Packagist](https://img.shields.io/packagist/php-v/mrgoodbytes8667/kernel-pack?logo=php&logoColor=FFF&style=flat)](https://packagist.org/packages/mrgoodbytes8667/kernel-pack)
![Symfony Version](https://img.shields.io/endpoint?url=https%3A%2F%2Fshields.mrgoodbytes.dev%2Fshield%2Fsymfony%2F%255E5.2%2520%257C%2520%255E6.0&logoColor=FFF&style=flat)
![Packagist License](https://img.shields.io/packagist/l/mrgoodbytes8667/kernel-pack?style=flat)    
A pack whose recipe sets up a kernel with alternate cache and log paths

## Installation

Make sure Composer is installed globally, as explained in the
[installation chapter](https://getcomposer.org/doc/00-intro.md)
of the Composer documentation.

### Applications that use Symfony Flex

Ensure you are running [symfony/flex](https://github.com/symfony/flex) 1.17 or greater to support [serverless flex recipes](https://symfony.com/blog/symfony-flex-is-going-serverless)

Add the [mrgoodbytes8667 recipes repository](https://github.com/mrgoodbytes8667/recipes) to your composer.json

```json
"extra": {
    "symfony": {
        "allow-contrib": true,
        "endpoint": "https://api.github.com/repos/mrgoodbytes8667/recipes/contents/index.json?ref=flex/main"
    }
}
```

Open a command console, enter your project directory and execute:

```console
$ composer require mrgoodbytes8667/kernel-pack
```
