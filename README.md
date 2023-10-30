How to launch ?

run these commands in the Calendar folder :
1. Installing composer
   - php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
   - php composer-setup.php
   - php composer.phar install
1. Initializing database & launching server
   - php artisan migrate
   - php artisan key:generate
   - php artisan serve
