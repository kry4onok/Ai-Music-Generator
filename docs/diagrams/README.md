# Диаграммы AI Music Generator

[Контейнеры и данные](architecture.svg) и [прямые вызовы с протоколами](integrations.svg) встроены в корневой README. Они показывают текущий прототип; связи с пометкой «план» ещё не работают.

SVG собираются из одноимённых `.puml` с помощью PlantUML и встроенной библиотеки C4-PlantUML. Оформление повторяет схемы командного проекта Smart Credit.

## Обновление SVG

Нужны PlantUML с C4-stdlib и Graphviz. Из корня репозитория:

```bash
plantuml -checkonly docs/diagrams/*.puml
plantuml -tsvg docs/diagrams/*.puml
```

Если PlantUML установлен как JAR, используйте `java -jar /путь/к/plantuml.jar` вместо `plantuml`.
