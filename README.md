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

Update debian from php7.0 to php7.3
```
sudo apt install ca-certificates apt-transport-https
wget -q https://packages.sury.org/php/apt.gpg -O- | sudo apt-key add -
echo "deb https://packages.sury.org/php/ stretch main" | sudo tee /etc/apt/sources.list.d/php.list
sudo apt update
sudo apt install php7.3 php7.3-cli php7.3-common php7.3-curl php7.3-mbstring php7.3-mysql php7.3-xml php7.3-gd
sudo apt-get purge php7.0-common
sudo apt install phpmyadmin*
sudo a2enmod php7.3
sudo /etc/init.d/apache2  restart
```
