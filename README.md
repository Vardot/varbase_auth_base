# Varbase Auth Base

A base recipe to install and configure Varbase Social Single Sign-On with default social authentication modules and configurations.

This recipe provides social authentication functionality, allowing users to log in using existing information from social networking services such as Google, Facebook, LinkedIn, and Twitter.

## Features

- Social Single Sign-On via Social Auth module
- Google social authentication enabled by default
- Gin theme social auth login block configuration
- Support for Google, Facebook, and LinkedIn social login

## Installation

Add the recipe using composer:
```
composer require drupal/varbase_auth_base:~1.0.0
```

Change directory to `/web` or `/docroot`

Run the Drupal recipe bash script:
```
bash core/scripts/drupal recipe recipes/contrib/varbase_auth_base
```

or

Run the Drush recipe command:
```
drush recipe recipes/contrib/varbase_auth_base
```

## Use With [Varbase](https://www.drupal.org/project/varbase) Distribution

This recipe is best used with [Varbase](https://www.drupal.org/project/varbase) distribution.

Can be installed with any Drupal site, even if installed with the Minimal or Standard profile.
However, using it with [Varbase](https://www.drupal.org/project/varbase) gives you way much more cool stuff!

## [Varbase documentation](https://docs.varbase.vardot.com/)

Check out Varbase documentation for more details.

Join Our Slack Team for Feedback and Support
http://slack.varbase.vardot.com/

This recipe is sponsored and developed by [Vardot](https://www.drupal.org/vardot).
