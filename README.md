# Dtech Module Base

    ``dtech/module-base``

 - [Main Functionalities](#user-content-main-functionalities)
 - [Installation](#user-content-installation)


## Main Functionalities

  This is core module of dtech which is require for other dtech modules.

## Installation
\* = in production please use the `--keep-generated` option

### Type 1: Zip file

 - Unzip the zip file in `app/code/Dtech`
 - Enable the module by running `php bin/magento module:enable Dtech_Base`
 - Apply database updates by running `php bin/magento setup:upgrade`\*
 - Flush the cache by running `php bin/magento cache:flush`

### Type 2: Composer
 - If you do not know what Composer is, please read [this](https://getcomposer.org/doc/00-intro.md) first.
 - Install the module composer by running `composer require dtech/module-base`
 - enable the module by running `php bin/magento module:enable Dtech_Base`
 - apply database updates by running `php bin/magento setup:upgrade`\*
 - Flush the cache by running `php bin/magento cache:flush`


