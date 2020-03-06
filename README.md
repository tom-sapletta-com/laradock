# laradock
Docker for Laravel


https://geshan.com.np/blog/2015/10/getting-started-with-laravel-mariadb-mysql-docker/

#fix permisssion
    docker exec -it laradock_front_1 chmod 0777 /var/www -R

#fix permisssion
    docker exec -it laradock_front_1 /bin/sh

docker-compose up

# force rebuild of Dockerfiles    
    docker-compose up -d --build
    
    docker-compose up -d --build --force
    
# start containers in background    
    docker-compose up -d
    
## others    
    docker-compose kill          # stop containers
    docker-compose up -d --build 
    docker-compose rm            # remove stopped containers
    docker ps                    # see list of running containers
    docker exec -ti [NAME] bash
        
php artisan backup:run

## START PROJECT
artisan tinker

## Version   of LAravel
    php artisan --version
    http://localhost:8000/laravelVersion
    
## Default Migration
https://laravel.com/docs/5.3/migrations


## Create DB Migration
https://github.com/laracasts/Laravel-5-Generators-Extended
##RUN
php artisan migrate:generate    

## MyAdmin
http://localhost/phpmyadmin/db_export.php?db=bubihr

http://192.168.233.128/phpmyadmin/

## Laravel-5-Generators
https://github.com/laracasts/Laravel-5-Generators-Extended#database-seeders

### DB Schema
php artisan make:migration:schema users

### Database Seeders
php artisan make:seed users

## Laravel Migrations Generator
https://github.com/Xethron/migrations-generator
    
#### Run 
    php artisan make:migrate:generate    

to create migrations for all the tables, or you can specify the tables you wish to generate using php artisan migrate:generate table1,table2,table3,table4,table5. You can also ignore tables with --ignore="table3,table4,table5"

Run php artisan help migrate:generate for a list of options.

### SEED
https://github.com/orangehill/iseed

php artisan iseed branch_list,branch_list_backup,branch_list_old,minijobbers,motions,timesheets,timesheets_lock_dates,users,users_data,users_question --force

## TEST DB
https://kyleferg.com/laravel-development-with-docker/

http://127.0.0.1:8000/testDatabase


## START
http://bubihr/admin/aushilfen/kellner-uebersicht/

    
# Laravel PHP Framework

[![Build Status](https://travis-ci.org/laravel/framework.svg)](https://travis-ci.org/laravel/framework)
[![Total Downloads](https://poser.pugx.org/laravel/framework/d/total.svg)](https://packagist.org/packages/laravel/framework)
[![Latest Stable Version](https://poser.pugx.org/laravel/framework/v/stable.svg)](https://packagist.org/packages/laravel/framework)
[![Latest Unstable Version](https://poser.pugx.org/laravel/framework/v/unstable.svg)](https://packagist.org/packages/laravel/framework)
[![License](https://poser.pugx.org/laravel/framework/license.svg)](https://packagist.org/packages/laravel/framework)

