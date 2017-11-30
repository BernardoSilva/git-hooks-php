# git-hooks-php

[![Latest Stable Version](https://poser.pugx.org/bernardosilva/git-hooks-php/v/stable)](https://packagist.org/packages/bernardosilva/git-hooks-php)
[![Monthly Downloads](https://poser.pugx.org/bernardosilva/git-hooks-php/d/monthly)](https://packagist.org/packages/bernardosilva/git-hooks-php)
[![Total Downloads](https://poser.pugx.org/bernardosilva/git-hooks-php/downloads)](https://packagist.org/packages/bernardosilva/git-hooks-php) 
[![License](https://img.shields.io/packagist/l/bernardosilva/git-hooks-php.svg)](https://packagist.org/packages/bernardosilva/git-hooks-php)

This is a [`git-hook` package](https://github.com/BernardoSilva/git-hooks-installer-plugin#git-hook-package) that contains some standards I want to use on all my PHP projects.

I use the git `pre-commit` hook to validate all my code before every commit to ensure
that my code is always valid.

[View how to create your own git-hook package](https://github.com/BernardoSilva/git-hooks-installer-plugin#how-to-create-my-git-hook-packages)

## How to install

Just add this package as a dependency on your project.

```sh
php composer.phar require bernardosilva/git-hooks-php
```

## pre-commit

Currently my pre-commit hook is checking for `PSR2` coding standards
that are not met using [php_codesniffer tool](https://github.com/squizlabs/php_codesniffer).


## How to contribute

* Create a Pull Request
* Suggest new ideas or open new detected issues

## Created by

* [Bernardo Silva](https://www.bernardosilva.com)

## License

MIT © [Bernardo Silva](https://www.bernardosilva.com)