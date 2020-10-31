# Magento 2 Module Develo IndexerLoopFix

    develo/module-indexerloopfix


## Main Functionality
Fixes the Magento Indexer Loop bug https://github.com/magento/magento2/pull/29196
As this PR will be in Magento 2.4.2, this applies the core PR code and fixes the issue in earlier versions, tested in 2.3.5-p1


## Installation

### Type 1: Composer (Preferred)

 - Install the module composer by running `composer require develo/module-indexerloopfix` \*
 - enable the module by running `php bin/magento module:enable Develo_IndexerLoopFix`
 - Flush the cache by running `php bin/magento cache:flush`
 
 \* in production please use the `--keep-generated` option

### Type 2: Zip file

 - Download and Unzip the folder into the new dir structure `app/code/Develo/IndexerLoopFix`
 - Enable the module by running `php bin/magento module:enable Develo_IndexerLoopFix`
 - Flush the cache by running `php bin/magento cache:flush`
