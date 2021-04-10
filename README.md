# Laravel and Vue.js 


## Steps to run


Change the following line in.env configuration file:

DB_CONNECTION=sqlite
DB_DATABASE=database.sqlite

Install sqlite in your computer.

----------------

Install the dependencies:

```
npm install
composer install
composer update
```

Generate Laravel Keys:

```
php artisan key:generate
```

Migrate and seed your local database:

```
php artisan migrate --seed
```

Compile the front-end:

```
npm run prod
```

Run the server:

```
php artisan serve
```


# laravelvuejs
