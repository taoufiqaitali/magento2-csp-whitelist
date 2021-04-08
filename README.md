# Magento 2 Content Security Policy whitelist

Allow Content Security Policy in Magento2

* Developer: Taoufiq Ait Ali
* Website: http://asktaw.com
* Contact: <mailto:contact@asktaw.com>


### Manual Installation

 * Unzip the file
 * Create a folder {Magento root}/app/code/Taitali/Csp
 * Copy the content from the unzip folder

## Enable extension

```
php bin/magento module:enable Taitali_Csp
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento cache:flush
php bin/magento setup:static-content:deploy
```
