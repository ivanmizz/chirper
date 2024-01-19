
# Chirper

A microblogging platform built using the php laravel framework and vuejs. This project is from the laravel bootcamp. The purpose was to learn the laravel framework while getting hands on. 

## Tech Stack
Built by Laravel, Vue & Mysql.

## Running the project 

**Prerequisites**: Composer, PHP 8.1, Node.

Download or clone this repository    
```
 https://github.com/ivanmizz/servicehub-2.git
```
Install dependencies  
  ```sh
  composer install
  ```  
  Incase of errors update dependencies using `composer update`    

Copy the .env.example into a newly created .env file , then edit credentials for your database.

Generate key:  
```sh
 php artisan key:generate
```    
Run database migration
  
```sh
 php artisan migrate
``` 
Start the backend development server  
```
  php artisan serve
```
Open new terminal to start frontend development server  
```
 npm run dev
```
Update the dependencies by `npm install` incase of errors

**Open in your browser**  
```
http://localhost:8000
```


