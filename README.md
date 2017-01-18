# Multi Instances Web App

As said in the title, multi instance <br/>
Updated to be compatible with Yunohost 2.4<br/>
Compliant with package_linter checks<br/>
Doing its best to be compliant with package_check too.<br/>
<br/>
* Beware !<br/>
Use this master version at your own risks !<br/>
For latest stable version, use the official community app (see https://github.com/YunoHost/apps for details on how to add the community list of apps inside your yunohost)<br/>
<br/>
* Functions :<br/>
No FTP Support<br/>
Backup or restore scripts <br/>
Ability to create database<br/>
<br/>
Simply copy the sources of your web page in /var/www/webapp_multi/$domain/$path/<br/>
Creation of a dedicated php-fpm socket<br/>
<br/>
<br/>
* Comment regarding the upgrade script<br/>
As this is a "generic" app, I choose not to upgrade the nginx and phpfpm conf files as you would more likely have had to update these.<br/>
If you have a problem with these and wish to come back to the generic file, simply delete the current file before upgrading (we check if nginx.conf exists and if not copy a generic one)<br/>
