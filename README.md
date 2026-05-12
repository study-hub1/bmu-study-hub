# 📚 BMU Study Hub

Учебная платформа для студентов British Management University.

## Как задеплоить на Railway

### 1. Загрузи на GitHub
1. Создай новый репозиторий на GitHub (например, `bmu-study-hub`)
2. Загрузи все эти файлы в репозиторий

### 2. Задеплой на Railway
1. Зайди на [railway.app](https://railway.app)
2. **New Project → Deploy from GitHub repo**
3. Выбери свой репозиторий `bmu-study-hub`
4. Railway автоматически запустит сайт

### 3. Получи ссылку
1. В проекте: **Settings → Networking → Generate Domain**
2. Твой сайт будет доступен по адресу `https://bmu-study-hub.up.railway.app`

## Структура файлов

```
bmu-study-hub/
├── index.html       ← Основной сайт
├── package.json     ← Конфигурация Node.js
├── nixpacks.toml    ← Конфигурация Railway
├── .gitignore
└── README.md
```

## Возможности сайта

- 📖 Теория по 7 предметам
- ✏️ MCQ тесты
- 🃏 Флэшкарты
- ⚡ True/False тесты
- 📖 Глоссарий
- 🎬 Видео
- 🤖 ИИ-преподаватель (Claude AI)
