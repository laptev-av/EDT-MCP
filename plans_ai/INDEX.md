# Реестр планов (plans_ai)

Сопоставление: GitHub issue ↔ файл плана ↔ обзор для человека ↔ статус.

## Соглашения

- Имя файла плана включает номер issue: `<issue>-<краткое-имя>.md` (например `129-form-tooling.md`).
- В начале файла плана — frontmatter с полями `issue`, `issue_url`, `title`, `overview`, `todos`, и опционально `status`.
- Человеко-ориентированный обзор результата — в `build/issues_<issue>.md`.
- Статусы: `planned` → `in-progress` → `done` (или `on-hold` / `dropped`).

## Планы

| Issue | План | Обзор | Статус |
|---|---|---|---|
| [#129](https://github.com/DitriXNew/EDT-MCP/issues/129) — Генерация форм и редактирование формы (и её элементов) | [129-form-tooling.md](129-form-tooling.md) | [build/issues_129.md](../build/issues_129.md) | planned |
