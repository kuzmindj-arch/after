# API Tests for DemoQA

## Коллекция Postman
Скачайте [DemoQA-API-Collection.json](./DemoQA-API-Collection.json) и импортируйте в Postman.

## Запросы в коллекции
- GET /Books — получить список всех книг
- GET /Book by ISBN — получить книгу по ISBN
- POST /User (negative) — попытка создать пользователя, который уже существует в системе.

## Статус тестирования
✅ Базовые запросы работают
✅ Негативные сценарии обрабатываются корректно