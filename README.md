# mallku-app (backend laravel)

## How to installation

Since this tech stack using PHP and MySQL, i assumed you have been installed those
Step by step installation :

- Installing PHP 8.0.x : https://linuxhint.com/install-php-8-ubuntu-22-04/

- Installing MySQL : https://www.digitalocean.com/community/tutorials/how-to-install-mysql-on-ubuntu-22-04

- Installing composer : https://www.digitalocean.com/community/tutorials/how-to-install-and-use-composer-on-ubuntu-22-04



## How to run

1. Update the .env file, according to your configuration (especially DB credential)
2. Goto `backend-laravel` main dir, then run the command `composer install`

3. Run the database migration : `php artisan migrate` (if there is command for create new DB -> yes)
4. Run the php artisan serve


# mallku-app (frontend react js)

## How to installation

Requirements : node js and npm

We use NVM for node js and npm installation

Step by step installation are : 
- Install `nvm` (https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-20-04#option-3-installing-node-using-the-node-version-manager)
- Install node js : `nvm install node`
- Install npm : `sudo apt-get install npm`

## How to run 
1. node install
2. node start
3. then the browser being opened at http://localhost:3000

![Screenshot from 2024-09-08 13-31-31](https://github.com/user-attachments/assets/4af1b494-91b2-4ae4-9688-59ac259e2596)


