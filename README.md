# Романтическое приглашение 💗

## Запуск
Открой папку в Visual Studio Code и запусти `index.html` через расширение Live Server.

## Важно: доступные даты
Открой `app.js`, найди `CONFIG.availableDates` и оставь там только дни, когда ты действительно свободен. Формат даты — `YYYY-MM-DD`.
Сайт показывает только эти даты, начиная с 10 декабря 2026 года. Если список пустой или все даты уже прошли, список покажет «Пока нет доступных дат».

Пример:
```js
availableDates: [
  "2026-12-10",
  "2026-12-13",
  "2026-12-17"
],
```

## Места
В `CONFIG.places` замени примеры на реальные названия и адреса парков/кофеен. Карта Google строится по адресу.

## Google Calendar
Вставь OAuth Client ID в `googleClientId`. Включи Google Calendar API в Google Cloud, создай OAuth Client типа Web application и добавь origin локального сервера и GitHub Pages. Подробная инструкция по настройке OAuth — в предыдущей версии README/настройках Google Cloud. Client Secret в браузер не вставляй.

## GitHub Pages
Загрузи файлы в репозиторий и включи Settings → Pages → Deploy from a branch → main → /(root).
