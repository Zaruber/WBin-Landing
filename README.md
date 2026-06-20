# WBin — лендинг

Лендинг-страница экосистемы **WBin** — расширения аналитики Wildberries для продавцов и менеджеров.

🔗 **Расширение:** [Chrome Web Store](https://chromewebstore.google.com/detail/dkpbihfjchandhkllkmljeijnlignhpk?utm_source=item-share-cb)
💬 **Сообщество:** [Telegram](https://t.me/+3g9fjC4OTn03MWYx)

## Состав

| Файл | Назначение |
|------|------------|
| `index.html` | Главная страница лендинга |
| `privacy.html` | Политика конфиденциальности |
| `image/` | Логотипы и иконки |

Статичный сайт без сборки и зависимостей — только HTML/CSS (шрифты подключаются с Google Fonts).

## Локальный просмотр

Откройте `index.html` в браузере или поднимите простой сервер:

```bash
python3 -m http.server 8000
# затем http://localhost:8000
```

## Хостинг на GitHub Pages

1. Создайте **публичный** репозиторий и запушьте содержимое этой папки.
2. Settings → Pages → Source: **Deploy from a branch** → ветка `main`, папка `/ (root)`.
3. Через минуту сайт будет доступен по адресу `https://<username>.github.io/<repo>/`.
