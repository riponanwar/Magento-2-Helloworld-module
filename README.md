Magento 2-Hello World Module
Learn how to create a hello world module in Magento 2

After create the module if you run the command as:

php bin/magento module:status

To enable a module in Magento 2

php bin/magento module:enable Zendanwar_Magetigers

Please upgrade your database: Run bin/magento setup:upgrade from the Magento root directory.

Let run the following command:

php bin/magento setup:upgrade

Please run the deloy command line to fix it.

php bin/magento setup:static-content:deploy

Route’s in magento are divided into 3 parts: Route frontname, controller and action as following example:

http://domainname.com/index.php/frontname/controller/action

After completed, please run to check result
php bin/magento cache:clean 

Finally brows the following 

http://domainname.com/magetigers/index/hello
