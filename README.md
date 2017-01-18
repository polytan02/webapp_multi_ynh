# Multi Instances Web App

As said in the title, multi instance
Updated to be compatible with Yunohost 2.4
Compliant with package_linter checks

* Beware !
Use this master version at your own risks !
For latest stable version, use the official community app (see https://github.com/YunoHost/apps for details on how to add the community list of apps inside your yunohost)

* Functions :
No FTP Support
No backup or restore scripts 
To be done : option for database creation

Simply copy the sources of your web page in /var/www/webapp_multi/$domain/$path/
Creation of a dedicated php-fpm socket


* Comment regarding the upgrade script
As this is a "generic" app, I choose not to upgrade the nginx and phpfpm conf files.
If you ahve a problem with these and wish to come back to the generic file, simply delete the current file before upgrading
