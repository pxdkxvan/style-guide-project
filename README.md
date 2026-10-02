# Style Guide Project

Учебный проект в подходе Docs as Code. В нём собраны правила для авторов
документации цифрового продукта: от выбора терминов до оформления примеров кода.

## Быстрый старт

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
mkdocs serve
```

После запуска сайт доступен по адресу `http://127.0.0.1:8000`.

## Проверка

```powershell
npx --yes markdownlint-cli@0.45.0 "**/*.md" "#site"
mkdocs build --strict
```

Правила совместной работы описаны в [CONTRIBUTING.md](CONTRIBUTING.md),
а этапы выполнения — в [REPORT.md](REPORT.md).
