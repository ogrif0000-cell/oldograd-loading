OLDOGRAD RP — статичный загрузочный экран

1. Загрузите index.html и loading.png на любой публичный HTTPS-хостинг.
   Примеры: GitHub Pages, обычный веб-хостинг, VPS с nginx/Apache.

2. Проверьте, что ссылка на index.html открывается в обычном браузере без авторизации.

3. В garrysmod/cfg/server.cfg добавьте:
   sv_loadingurl "https://ВАШ-ДОМЕН/index.html"

4. Перезапустите сервер.

Важно:
- Используйте HTTPS.
- Файлы должны быть доступны публично.
- Картинку в addons/ или Workshop класть недостаточно: sv_loadingurl открывает веб-страницу.
