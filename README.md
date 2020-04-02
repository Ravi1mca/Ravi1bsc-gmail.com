Installation
Clone repository
$ git clone repository
Enter folder
$ cd concussion
Install composer dependencies
 composer install
Generate APP_KEY
 php artisan key:generate
Configure .env file, edit file with next command $ nano .env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=database
DB_USERNAME=user
DB_PASSWORD=secret
MAIL_DRIVER=smtp MAIL_HOST=smtp.gmail.com MAIL_PORT=587 MAIL_USERNAME=mymail@gmail.com MAIL_PASSWORD=secret MAIL_ENCRYPTION=TLS

Run migrations
 php artisan migrate
Create client
php artisan passport:install
