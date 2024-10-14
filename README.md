# Droptica's Drupal Recipes: CAPTCHA

## Recipe description

This Recipe enhances security by implementing the CAPTCHA module, which provides challenge-response tests to determine whether the user is human, protecting against spam and automated submissions on your Drupal site.

After installing the Recipe, customize the settings on this page:
- `/admin/config/people/captcha`

## Download recipe

```shell
composer require droptica/ddr_security_captcha
```

## Installation

```shell
drush recipe recipes/contrib/ddr_security_captcha
```

## Features

- Installs the CAPTCHA module
- Configures basic CAPTCHA settings
- Adds CAPTCHA protection to user registration and login forms

## Module Dependencies

- [CAPTCHA](https://www.drupal.org/project/captcha)

## How to report issues and new features requests

Go to project page (@todo url) and create an issue.

## Do you need a Drupal Recipe for your project?

Contact us if you need support in creating a custom Drupal Recipe.

## Contact

https://www.droptica.com/drupal-recipes

## Changelog

### 2024-10-14
First version of the recipe.
