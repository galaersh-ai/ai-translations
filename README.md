# AI Translations

Переводы материалов по AI-системам, агентам и паттернам проектирования.

Сайт: `https://galaersh-ai.github.io/ai-translations/`

## Структура

```
docs/
  index.md/.ru.md           — главная страница
  patterns/                 — agent-patterns (оригинал + перевод)
    index.md/.ru.md
    patterns/               — каталог паттернов
    concepts/               — концептуальные статьи
    guides/                 — руководства
    api/                    — API-документация
  other/                    — другие переводы
    index.md/.ru.md
```

## Как переводить

1. Найди `.md`-файл оригинала (например `patterns/patterns/react.md`)
2. Создай `.ru.md`-версию рядом: `patterns/patterns/react.ru.md`
3. Переведи содержание
4. `git push` — сайт обновится автоматически

## Локальный запуск

```bash
pip install -r requirements.txt
mkdocs serve
```

Открой http://localhost:8000

## Лицензия

Оригиналы принадлежат [osok/agent-patterns](https://github.com/osok/agent-patterns) (MIT).  
Переводы — CC BY 4.0.
