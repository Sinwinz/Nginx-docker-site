## Nginx docker site
Суть репозитория упростить самому себе жизнь.
Скрипт-установщик копирует содержимое репозитория и запускает docker с веб сервером nginx.
Подходит для небольших сайтов.
Чтобы поднять веб-cтраницу подлейте index.html в каталог docker-compose и перезапустите контейнер.

## Скрипт-установщик
```bash
cd /opt/
mkdir site
cd site
git clone https://github.com/Sinwinz/Nginx-docker-web.git
cd Nginx-docker-web
docker compose up -d
```
