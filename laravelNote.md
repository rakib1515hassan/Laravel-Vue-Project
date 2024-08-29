# Laravel Project Management Guide

## Project Setup

### Create a New Project


# To create Project
    >> composer create-project --prefer-dist laravel/laravel <your_project_name>

    >> php artisan key:generate

    >> php artisan serve

    >>  php artisan serve --host=0.0.0.0 --port=<Port No>
    EX: php artisan serve --host=0.0.0.0 --port=8001


# Srorage Link
    >> php artisan storage:link


# Create Migrations Table
    >> php artisan make:migration create_<table_name>_table

    >> php artisan migrate

    >>  php artisan migrate --path=<Path>/<Migration Name>
    EX: php artisan migrate --path=database/migrations/2024_04_17_123039_create_memberships_table.php


# Roll Back Migration
    >>  php artisan migrate:rollback 

    >>  php artisan migrate:rollback --path=<Path>/<Migration Name>
    EX: php artisan migrate:rollback --path=database/migrations/2024_04_17_123039_create_memberships_table.php


# Create Model
    >> php artisan make:model <Model Name>
    EX: php artisan make:model Institutions


# Create Controller
    >>  php artisan make:controller <Controller Name> 
    EX: php artisan make:controller UserController 

    >>  php artisan make:controller <Controller Name> --resource
    EX: php artisan make:controller UserController --resource

    >> php artisan make:controller <Path Name>/<Controller Name> --resource
    EX: php artisan make:controller api/PhotoCoUserControllerntroller --resource



# Create Seeder
    >> php artisan make:seeder <Seeder Name>

    >> php artisan db:seed



# Create Model, Migration, Seeder and Controller 
    >> php artisan make:model <Model Name> -msc
    >> php artisan make:model <Model Name> -m  (Model and Migrate)


# Optimize the Application
    >> php artisan optimize


# Clear Application Cache
    >> php artisan cache:clear


# Clear View Cache
    >> php artisan view:clear


# Clear Config Cache
    >> php artisan config:cache


# Clear Route Cache
    >> php artisan route:cache


# List All Artisan Commands
    >> php artisan list


# Clear Config Cache
    >> php artisan config:cache




### Key Points:
- **Markdown Formatting**: Used proper Markdown syntax to enhance readability.
- **Sections and Subsections**: Organized into clear sections for easy navigation.
- **Examples**: Provided examples where applicable to demonstrate usage.

