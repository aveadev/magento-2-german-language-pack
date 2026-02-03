## Magento 2 German Language Pack

**Install German language pack**:

``` php
composer require aveadev/magento-2-german-language-pack:dev-main
php bin/magento setup:static-content:deploy de_DE
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush
```
