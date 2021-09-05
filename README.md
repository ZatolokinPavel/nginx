# Конфиги для сервера Nginx

Подключение:
1. Скачать этот проект в директорию `/srv`.
2. Создать символьную ссылку на основной конфиг
   ```bash
   cd /etc/nginx/sites-enabled
   sudo ln -s /srv/nginx/nginx.cfg okfilm.com.ua
   ```
3. Создать символьную ссылку на папку includes
   ```shell
   cd /etc/nginx/includes
   sudo ln -s /srv/nginx/includes/ okfilm
   ```
4. Применить: `sudo nginx -s reload`
