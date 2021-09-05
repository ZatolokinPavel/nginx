# Конфиги для сервера Nginx

Подключение:
1. Скачать этот проект в директорию `/srv`.
2. Удалить символьную ссылку `/etc/nginx/sites-enabled/default`
3. Создать символьную ссылку на основной конфиг  
   `sudo ln -s /srv/nginx/nginx.cfg /etc/nginx/sites-enabled/okfilm.com.ua`
4. Создать папку `/etc/nginx/includes`
5. Создать символьную ссылку на мою папку includes  
   `sudo ln -s /srv/nginx/includes/ /etc/nginx/includes/okfilm`
6. Применить: `sudo nginx -s reload`
