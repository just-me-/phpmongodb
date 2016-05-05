 * @package PHPmongoDB
 * @version 1.0.1
==============================================================================================================
 Introduction
==============================================================================================================
 A Tool available for administrative work of MongoDB over Web - freely available. Forked from [PHPmongoDB](https://github.com/phpmongodb/phpmongodb).

==============================================================================================================
Installation
==============================================================================================================
1. Install PHP Webserver like APACHE, NGINX, HTTPD if you don't have one
2. Install MongoDB PHP driver (http://us.php.net/manual/en/mongo.installation.php)
3. Download the package `git clone https://github.com/phpmongodb/phpmongodb.git`
4. Copy the default config `cp -p config.php.default config.php`
5. Open the config.php with your editor (e.g. `vim config.php`) and change host, port, admins etc. Default given below:
   -Server Setting
     'name' => "Localhost",
     'server'=>false,
     'host' => "127.0.0.1",
     'port'=>"27017",
     'timeout'=>0,
   - Make authentication = TRUE for using your MongoDB user and password.
   - Make authorization['readonly'] = TRUE for making your MongoDb readonly.
6. Visit the index.php in your browser, for example: http://localhost/phpmongodb
7. Login with admin username and password, which is set "admin" and "admin" as default
8. Start playing with your MongoDBs!

==============================================================================================================
Upgradation 
==============================================================================================================
Just keep your settings from config.php
