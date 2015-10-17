# git-hooks-php

This is a [`git-hook` package](https://github.com/BernardoSilva/git-hooks-installer-plugin#git-hook-package) that contains some standards I want to use on all my PHP projects.

I use the git `pre-commit` hook to validate all my code before every commit to ensure
that my code is always valid.

[View how to create your own git-hook package](https://github.com/BernardoSilva/git-hooks-installer-plugin#how-to-create-my-git-hook-packages)

## How to install

Just add this package as a dependency on your project.

```sh
php composer.phar require bernardosilva/git-hooks-php
```

On my projects I always use a `/bin` directory and this `pre-commit` script require those path's to work.

You can set your bin directory on your `composer.json` file

```json
"config": {
    "bin-dir": "bin"
}
```

## pre-commit

Currently my pre-commit hook is checking for PSR2 coding standards that are not met.
Use this package to detect that:

* [squizlabs/php_codesniffer](https://github.com/squizlabs/php_codesniffer)


## How to contribute

* Create a Pull Request
* Suggest new ideas or open new detected issues