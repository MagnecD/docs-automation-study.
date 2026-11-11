# Автоматизация разработки технической документации

Учебный проект по практической работе 3.4.

## Содержание
- `index.md` — главная страница сайта GitHub Pages.
- `docs/01_intro.md` — введение.
- `docs/02_api.md` — описание API.
- `docs/03_report.md` — отчёт о работе.
- `diagrams/process.puml` — исходный текст схемы PlantUML.
- `diagrams/process.svg` — готовая схема для сайта.
- `api/openapi.yaml` — описание API в формате OpenAPI.

## Публикация
В репозитории GitHub откройте **Settings → Pages**. В разделе Build and deployment выберите:
- Source: Deploy from a branch
- Branch: `main`
- Folder: `/ (root)`

Нажмите Save. Адрес сайта будет иметь вид:
`https://ВАШ-ЛОГИН.github.io/docs-automation-study/`
