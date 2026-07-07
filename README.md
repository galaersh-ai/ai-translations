# AI Translations

Переводы материалов по AI-системам, агентам и паттернам проектирования.

Сайт: `https://galaersh-ai.github.io/ai-translations/`

## Структура

```
docs/
  en/                       ← английская версия
    index.md
    patterns/               ← agent-patterns (оригинал)
    other/                  ← другие переводы
  ru/                       ← русская версия
    index.md
    patterns/               ← agent-patterns (перевод)
    other/                  ← другие переводы
```

## Как переводить

1. Найди `.md`-файл в `docs/en/` (например `docs/en/patterns/patterns/react.md`)
2. Создай такой же файл в `docs/ru/`: `docs/ru/patterns/patterns/react.md`
3. Переведи содержание
4. `git push` — сайт обновится автоматически

## Локальный запуск

```bash
pip install -r requirements.txt
mkdocs serve
```

Открой http://localhost:8000

## Лицензия

Оригиналы принадлежат [osok/agent-patterns](https://github.com/osok/agent-patterns) — MIT License.  
Переводы — CC BY 4.0 (требуется указание автора перевода).
