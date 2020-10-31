# Mage2 Module Develo IndexerLoopFix

    ``develo/module-indexerloopfix``

 - [Main Functionalities](#markdown-header-main-functionalities)
 - [Installation](#markdown-header-installation)


## Main Functionalities
Fixes the Magento Indexer Loop bug https://github.com/magento/magento2/pull/29196

## Installation
\* = in production please use the `--keep-generated` option

### Type 1: Zip file

 - Unzip the zip file in `app/code/Develo`
 - Enable the module by running `php bin/magento module:enable Develo_IndexerLoopFix`
 - Flush the cache by running `php bin/magento cache:flush`

### Type 2: Composer

 - Install the module composer by running `composer require develo/module-indexerloopfix`
 - enable the module by running `php bin/magento module:enable Develo_IndexerLoopFix`
 - Flush the cache by running `php bin/magento cache:flush`


