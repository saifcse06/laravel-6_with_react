 // create a new laravel project called crud
laravel new crud

// once done, get inside crud folder
cd crud

// laravel comes with vue js by default, lets change that to react
php artisan preset react

// Laravel 6 default auth
composer require laravel/ui
php artisan ui react --auth

// migrate
php artisan migrate

// install necessary packages from npm (node package manager)
npm install

// re-compile javascript assets every time you make a change (compulsory)
npm run watch
php artisan serve

// .env
DB_DATABASE=crud
DB_USERNAME=root
DB_PASSWORD=

 