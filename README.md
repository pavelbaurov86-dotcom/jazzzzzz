# Jazz Funk — одностраничный сайт курса

Этот репозиторий содержит статическую страницу курса (HTML/CSS/JS), готовую к публикации через **GitHub Pages**.

## Быстрый старт

1. Создайте репозиторий на GitHub и загрузите файлы из этой папки.
2. Убедитесь, что включены **Actions** в настройках репозитория (Settings → Actions → General → Allow all actions).
3. Перейдите в **Settings → Pages**, выберите **Build and deployment: GitHub Actions**.  
   После первого пуша workflow сам задеплоит сайт.
4. Ссылка на сайт появится внизу вкладки **Actions** в успешном прогоне `Deploy static site to Pages`
   и в **Settings → Pages**.

## Структура
```
.
├─ index.html                  # Ваша одностраничная страница
├─ .nojekyll                   # Отключает Jekyll на GitHub Pages
└─ .github/workflows/pages.yml # Автодеплой на GitHub Pages
```

## Локальный просмотр
Откройте `index.html` двойным кликом или запустите локальный сервер:
```bash
python3 -m http.server 8080
```
И перейдите на http://localhost:8080

## Изменения и обновления
Любой новый коммит в ветку `main` автоматически публикуется на GitHub Pages.
