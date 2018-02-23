# wordpress-40
WordPress 4.0 development project contains the codebase used to test my plugins. Projects is based on WordPress 4.0 core with symbolic links to shared themes and plugins. There are also other third-party plugins used to support my plugins and a "WordPress setup" plugin that is used to create a first setup for themes. It creates a custom taxonomy "genre", a custom post type "book" and contains a set of utility functions used in WordPress theme to test plugin functionalities.

First setup:
* cd /var/www/dev/
* git clone git@github.com:andrealandonio/wordpress-40.git wordpress40
* cd wordpress40
* sudo chown -R www-data:www-data wp-content/uploads (change uploads folder grants)
* cd ~/Projects/WordPress/Databases
* mysql -h localhost -u root -padmin wordpress_40 < wordpress_40.sql (restore database)

Local environment works on:
* 127.0.0.1   wordpress40.local
