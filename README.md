How to launch ?

Run these commands in the Calendar folder :
1. Installing composer
   - php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
   - php composer-setup.php
   - php composer.phar install
1. Initializing database & launching server
   - php artisan migrate
   - php artisan key:generate
   - php artisan serve

!!! Don't forget to create courses, groups, teachers because your database will be empty when cloning !!!
- Google Log in feature deprecated
