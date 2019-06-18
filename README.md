# Google Presentation-
## Google Cloud/Lamp/Laravel
Requirements for Laravel 5.7
```
PHP >= 7.1.3
BCMath PHP Extension
Ctype PHP Extension
JSON PHP Extension
Mbstring PHP Extension
OpenSSL PHP Extension
PDO PHP Extension
Tokenizer PHP Extension
XML PHP Extension
```

```
sudo git clone https://github.com/elminson/google-presentation-google-cloud_lamp_laravel.git todo
cd todo
sudo composer install
sudo chmod 777 storage/* -R
```
Update .env with your DB information
```
php artisan migrate
php artisan db:seed

```
