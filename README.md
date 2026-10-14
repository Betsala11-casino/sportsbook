# BetSala 11 Chile - static site (GitHub Pages)

## Структура
```
index.html                 главная (one-page)
assets/style.css           стили (desktop + 1100 / 900 / 640 / 420 px)
assets/main.js             бургер-меню, smooth scroll, активный пункт меню, reveal
assets/favicon.svg         иконка
assets/og.svg              OG-картинка
play-and-win/index.html    редирект на реф-ссылку (noindex)
404.html                   страница ошибки
robots.txt / sitemap.xml
.nojekyll                  отключает Jekyll на GitHub Pages
```

## Публикация
1. Создать репозиторий, залить все файлы в корень.
2. Settings -> Pages -> Source: `Deploy from a branch` -> `main` / `/ (root)`.
3. После деплоя заменить `SITE_URL` на реальный домен в `index.html`, `robots.txt`, `sitemap.xml`
   (например `user.github.io/repo` или свой домен через файл `CNAME`).

## Реф-ссылка
Все кнопки ведут на `play-and-win/` -> `https://betsalavip.com/affiliates/`.
Поменять цель: `play-and-win/index.html` (meta refresh + JS, 2 места).
