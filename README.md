# Simple lemp project using docker

Lemp : 

 * Nginx webserver (latest version)
 * Php-fpm (latest version)
 * mariadb (latest version)
 * Phpmyadmin (latest version)

## how to use:

1. first clone this repo
2. go to project directory `cd docker-lemp`
3. run command `docker-compose up -d` on your terminal
4. enjoy

## files and directories structure:

`logs` directory: contains logs of Nginx webserver
`mysql` directory: contains mariadb databases,logs, ...
`nginx` directory: contains nginx webserver config
`php` directory: contains php configs(php.ini)
`public` directory: this is webserver *document root*
