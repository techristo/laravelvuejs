# Laravel and Vue.js 


## Steps to run

Create .env file renaming the env.example file to .env

Change the following lines in.env configuration file:

DB_CONNECTION=sqlite

DB_DATABASE=database.sqlite

Install sqlite in your computer.

---------------------------------------------------------------

Install the dependencies:
---------------------------------------------------------------
npm install

composer install

composer update

--------------------------------------------------------

Generate Laravel Key
--------------------------------------------------------

php artisan key:generate

--------------------------------------------------------

Migrate and seed your local database:
------------------------------------------------------

php artisan migrate --seed

-------------------------------------------------------

Compile the front-end:
-------------------------------------------------------

npm run prod

-------------------------------------------------------

Run the server:
-------------------------------------------------------


php artisan serve



