# Как устроен этот репозиторий

## Почему Markdown

Markdown:

- хорошо diff-ится в Git;
- легко рецензируется в Pull Request;
- поддерживает код с подсветкой синтаксиса;
- позволяет строить Mermaid-схемы;
- хранит небольшие CSV/JSON/YAML-данные прямо рядом с условием;
- поддерживает checklist и collapsible-блоки;
- легко преобразуется в статический учебный сайт.

## Рекомендуемая работа преподавателя

```mermaid
gitGraph
   commit id: "syllabus"
   branch week-01
   commit id: "lecture 01"
   commit id: "lab 01"
   checkout main
   merge week-01
   branch fixes
   commit id: "clarifications"
   checkout main
   merge fixes
```
