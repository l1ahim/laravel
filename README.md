# laravel# Create a new project
composer create-project laravel/laravel mytube

# copy .env.example file to .env file

# generate a new app key:
php artisan key:generate

# from within the project run to serve the application and access it, it runs on port 8000:
php artisan serve

# user authentication:
php artisan make:auth

# .. it will create a new folder in resources/views called auth:
- it's possible to register, reset password, login

