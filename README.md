# IntegralService Test Metapackage

## What is it?

This project provides the essential bundles to test Symfony projects and insure code quality :

  - [PHPUnit](https://phpunit.de) with the [PHPUnit bridge for Symfony](https://github.com/symfony/phpunit-bridge)
  - [Behat](http://behat.org)  with [Mink](http://mink.behat.org) and some of its drivers :
    - [GoutteDriver](http://mink.behat.org/en/latest/drivers/goutte.html) for the [Goutte headless browser](http://mink.behat.org/en/latest/drivers/goutte.html)
    - [BrowserKitDriver](http://mink.behat.org/en/latest/drivers/browserkit.html) for the [Symfony BrowserKit component](http://symfony.com/components/BrowserKit)
    - [Selenium2Driver](http://mink.behat.org/en/latest/drivers/selenium2.html) for [Selenium2](http://seleniumhq.org)
  - Some extra Behat test contexts, such as [Behatch](https://travis-ci.com/IntegralService/BehatContext) and [IntegralService/BehatContext](https://github.com/IntegralService/BehatContext).
  - [Coding standard](https://github.com/djoos/Symfony-coding-standard) for Symfony projects
  - [PHP CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer)

## How to install

You can install this package with composer :

`composer require --dev integralservice/test-metapackage`

## How to contribute

We are more than pleased to receive pull request if you want to add some functionnalities
that can benefit the community.
