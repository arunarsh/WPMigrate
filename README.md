WordPress Migration
=====================

The purpose of this script is to quickly and easily allow the user to update all database references for a WordPress website. Instead of doing a manual, text find-and-replace, this script connects to your WordPress database and does all of the heavy lifting for you.

** WARNING! ** This script modifies the database as configured in your wp-config.php file. You should make a full backup of your database before using this script.

** SECURITY NOTICE ** This script should not be left on a live web server as it offers direct access to your database. When you're done with your migration, delete the script.

Script Installation
----------------------

* Ensure your wp-config.php file has the correct database connection settings.
* Upload the wp-migrate.php file into the root directory of your WordPress installation.
* Point your web browser to the script (like http://mywebsitedomain.com/wp-migrate.php)

Script Usage
-----------------------

* If your wp-config.php file is setup correctly, the script will determine the current "Old" website address.
* Set the "New URL" field to the absolute URL you'd like the database updated to.