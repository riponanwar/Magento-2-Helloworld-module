<h2>Magento 2-Hello World Module</h2>

<h3>Learn how to create a hello world module in Magento 2</h3>

After create the module if you run the command as:

<code>php bin/magento module:status </code>

To enable a module in Magento 2

<code>php bin/magento module:enable Zendanwar_Magetigers</code>

Please upgrade your database: Run bin/magento setup:upgrade from the Magento root directory.

Let run the following command:

<code>php bin/magento setup:upgrade</code>

Please run the deloy command line to fix it.

<code>php bin/magento setup:static-content:deploy</code>

Route’s in magento are divided into 3 parts: Route frontname, controller and action as following example:

<code>http://domainname.com/index.php/frontname/controller/action</code>

After completed, please run to check result
  
<code>php bin/magento cache:clean </code>

Finally brows the following 

<code>http://domainname.com/magetigers/index/hello</code>
