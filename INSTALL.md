## INSTALL DOOPHP Web Framework
![DooPHP](http://doophp.com/images/doologo.png "DooPHP")

Thank you for using DooPHP - a high performance MVC based PHP framework.


### INSTALLATION

Please make sure the release file is unpacked under a Web-accessible
directory. You have to put it under the root directory for the app & demos to work. 

You shall see the following files and directories:

		demos/                demos
		dooframework/         framework source files
		app/                  base of a project
		LICENSE.txt           license of DooPHP (LICENSE.md on this GitHub Version)
		README.txt            this file (README.md on this GitHub Version)
		CHANGELOG.txt         changes made in this version (CHANGELOG.md on this GitHub Version)


If you placed it elsewhere, please change the app or demos configurations in protected/config/common.conf.php

```php
	$config['SITE_PATH'] = 'C:/wamp/www/myfolderapp/';
	$config['BASE_PATH'] = 'C:/wamp/www/dooframework/';
```
	  
If your app is in a sub directory, please change the following setting:

```php
	$config['SUBFOLDER'] = '/myfolderapp/';
	// This example can be accessed at http://localhost/myfolderapp/
```

More details on installation can be found at http://www.doophp.com/doc/guide/start/install


### REQUIREMENTS

The minimum requirement by DooPHP is that your Web server supports **PHP 5.1.x** or above. DooPHP has been tested
with Apache 2 and Cherokee Web Server on Windows and Linux operating systems.

To use the database ORM you have to enable PDO extension.


### QUICK START

DooPHP comes with a directory call 'app'. It is the basic of a DooPHP application.
Change the Site path and project path configurations in */protected/config/common.conf.php*

The default configuration is for development purpose.


### WHAT's NEXT

Please visit the project website for tutorials, class reference
and join discussions with other DooPHP users.

<dl>
	<dt><b>DooPHP</b></dt>
	<dd>
		http://www.doophp.com
		<br>http://www.doophp.com/blog
		<br>http://www.doophp.com/forum
		<br>http://www.twitter.com/doophp
	</dd>
</dl>
