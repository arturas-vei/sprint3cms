# sprint3cms
CMS with Doctrine ORM and MVC architecture
A custom content management system created with raw PHP using Doctrine ORM, Composer and MVC architecture.

Launch
Clone repository to anywhere in www folder inside root AMPPS directory
1.png

Create sprint3 database on MySQL Workbench
3.png

Install composer if you haven't done that already:
https://getcomposer.org/download/

Run these commands in sprint3cms repository folder on terminal:
php composer.phar install
vendor\bin\doctrine orm:schema-tool:update --force --dump-sql (if you are using windows CMD)
vendor/bin/doctrine orm:schema-tool:update --force --dump-sql (if you are using git bash / mac / linux terminals)
php composer.phar dump-autoload
Open sprint3cms folder on localhost

If you want to add pages, just enter /admin after root url

Login details will be provided in input fields
