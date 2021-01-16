1. clone the repo and cd into it
1. `composer install`
1. make sure db is running and credentials are setup in config\database.php (or in your .env file).
1. If you have no .env file you can use the example one. Just rename .env.example to .env. Enter your db credentials here.
1. `php artisan key:generate`
1. `php artisan migrate`
1. `php artisan db:seed`
1. (Optional) `Run vendor/bin/phpunit` to run some application tests I have written. Have a look at them in the `tests` folder.
1. `php artisan serve`
1. Visit localhost:8000 in your browser
