# To create Project

    >> composer create-project --prefer-dist laravel/laravel <your_project_name>

    >> php artisan key:generate

    >> php artisan serve


# Create Migrations Table

    >> php artisan make:migration create_<table_name>_table

    >> php artisan migrate
    
    >>  php artisan migrate --path=<Path>/<Migration Name>
    EX: php artisan migrate --path=database/migrations/2024_04_17_123039_create_memberships_table.php

# Roll Back Migration
    >>  php artisan migrate:rollback 

    >>  php artisan migrate:rollback --path=<Path>/<Migration Name>
    EX: php artisan migrate:rollback --path=database/migrations/2024_04_17_123039_create_memberships_table.php
