# laravel8docker
 
This is to setup a local development environment for laravel + mysql using docker.  Tested with latest laravel 8.x and mysql 8.x.  

# How to setup

Prerequisite
1. Docker software on your local machine.  If you are using Windows or mac, the easiest is to install Docker Desktop (https://www.docker.com/products/docker-desktop)
2. You need to install git on your local machine.  (https://github.com/git-guides/install-git)

To setup laravel 8 environment for a project "Project A"
1. git clone http://github.com/barrychum/laravel8docker.git "Project A"
2. docker-compose up -d
3. docker-compose exec app composer create-project laravel/laravel=8.4 /var/www/html
4. docker-compose exec app php artisan key:generate
