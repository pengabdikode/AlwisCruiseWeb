<p align="center"><img src="https://imgur.com/a/Dpj1lkD"></p>

## About Alwis Cruise

Berdiri sejak tahun 2019, Alwis Cruise dipercaya 
sebagai salah satu agen cruise-line di Indonesia.

## Apa yang harus dilakuin sehabis clone?

1. php artisan key:generate

2. Setting .env dengan database dan email :
MAIL_DRIVER=smtp
MAIL_HOST=smtp.gmail.com
MAIL_PORT=587
MAIL_USERNAME=sikilteam@gmail.com
MAIL_PASSWORD=cwdwgzgeugvebngt
MAIL_ENCRYPTION=tls

3. php artisan storage:link

4. php artisan migrate --seed
