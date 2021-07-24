# ip-note

## Структура:
В папке ./app - файлы дев-версии
В папке ./build - файлы прод-версии, обработанные сборщиком Gulp

## Требования:
> **Node.js**

## Подготовка:
1. `npm init`
2. `npm install`

## Запуск сборщика дев-версии (watcher + browserSync):
- `npm run dev`

## Запуск сборщика прод-версии (builder):
- `npm build:prod`

## Примечания:
> Изменения скриптов и стилей производить **только в дев-версии**

> Кастомные стили и скрипты прописывать **в отдельных файлах**

> Для открытия конкретной модалки нужно вызвать функцию openModal(modalID)