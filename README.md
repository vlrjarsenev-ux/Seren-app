# Wellbeing App — Docs Site

Jekyll-сайт с фирменной темой Wellbeing App (тёплые пастельные тона).

## Структура

```
docs-site/
├── _config.yml       # Конфиг Jekyll
├── _layouts/
│   └── default.html  # Основной layout (header, nav, footer)
├── assets/
│   └── css/
│       └── style.css # Фирменные стили
├── index.md          # Главная
├── privacy.md
├── terms.md
├── delete-account.md
└── contact.md
```

## Деплой на GitHub Pages

1. Скопируй всё содержимое `docs-site/` в корень репозитория `vlrjarsenev-ux/wellbeing-app`
2. `git add .` → `git commit` → `git push`
3. В Settings → Pages: Source = Deploy from branch, Branch = main, Folder = / (root)

## baseurl

В `_config.yml` указан `baseurl: "/wellbeing-app"`. Если репозиторий называется иначе — измени на `"/имя-репо"`.
