# centreon/centreon-smarty

## Introduction
This repository is a fork of the original Smarty repository.
It is used to manage the version 3.1.48 of Smarty used in Centreon on version 22.10, 23.04, 23.10 to be
compatible with PHP 8.1.
Two branches have been created to manage the version 3.1.48 of Smarty :
- 3.1.48.x (stable)
- dev-3.1.48.x (develop)

On each release, a tag is created on the branch 3.1.48.x to use the last version of Smarty in Centreon by composer.

The tags will be in this following format : v.3.1.48+*-centreon where * is the minor of centreon.

## Requirements

centreon/centreon-smarty can be run with PHP 5.2 to PHP 8.2.

# smarty-php/smarty

## Smarty 3 template engine
[smarty.net](https://www.smarty.net/) 

[![Build Status](https://travis-ci.org/smarty-php/smarty.svg?branch=master)](https://travis-ci.org/smarty-php/smarty)

### Documentation

For documentation see 
[www.smarty.net/docs/en/](https://www.smarty.net/docs/en/) 

### Requirements

Smarty can be run with PHP 5.2 to PHP 7.2.

### Distribution repository

> Smarty 3.1.28 introduces run time template inheritance

> Read the NEW_FEATURES and INHERITANCE_RELEASE_NOTES file for recent extensions to Smarty 3.1 functionality

Smarty versions 3.1.11 or later are now on GitHub and can be installed with Composer.


The "smarty/smarty" package will start at libs/....   subfolder.

To get the latest stable version of Smarty 3.1 use:

```json
"require": {
    "smarty/smarty": "~3.1"
}
```

in your composer.json file.

To get the trunk version use:

```json
"require": {
    "smarty/smarty": "~3.1@dev"
}
```

For a specific version use something like:

```json
"require": {
    "smarty/smarty": "3.1.19"
}
```

PHPUnit test can be installed by corresponding composer entries like:

```json
"require": {
    "smarty/smarty-phpunit": "3.1.19"
}
```

Similar applies for the lexer/parser generator.

```json
"require": {
    "smarty/smarty-lexer": "3.1.19"
}
```

Or you could use:

```json
"require": {
    "smarty/smarty-dev": "3.1.19"
}
```

Which is a wrapper to install all 3 packages.

Composer can also be used for Smarty2 versions 2.6.24 to 2.6.30.
