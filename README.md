# site-cicd

Статический сайт с автоматическим деплоем на GitHub Pages через GitHub Actions.

## Что внутри

- `index.html` — главная страница сайта
- `style.css` — оформление
- `.github/workflows/deploy.yml` — workflow для автоматической публикации

## Как это работает

При каждом `push` в ветку `main` GitHub Actions автоматически:
1. Скачивает файлы репозитория
2. Готовит их к публикации
3. Публикует на GitHub Pages

Сайт доступен по адресу: https://murga-es.github.io/site-cicd/

## Автор

Филонова Е.С.
