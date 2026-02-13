# API Automation Tests (Postman) 🚀

![Tests](https://img.shields.io/badge/Tests-passing-success)
![Postman](https://img.shields.io/badge/Tool-Postman-orange)
![JavaScript](https://img.shields.io/badge/Language-JavaScript-yellow)

Автотесты для REST API (тестовый стенд JSONPlaceholder). Проверка CRUD-сценариев и валидация ответов.

## 🛠 Стек
* **Postman** — коллекция и окружение.
* **JavaScript (ES6)** — тесты и динамическая генерация данных.
* **SLA Verification** — проверка времени отклика.

## 📋 Реализованные проверки
* **CRUD**: Create, Read, Update, Delete.
* **Dynamic Data**: Генерация случайных имен/ID в Pre-request Script.
* **Assertions**: 
  * Статус-коды (200, 201, 204).
  * Валидация JSON-схемы.
  * SLA (Response time < 1200ms).

## 🚀 Запуск
1. Импорт `alfa_api_collection.json` и `stage_env.json` в Postman.
2. Выбор окружения **JSONPlaceholder-Stage**.
3. Запуск через **Collection Runner**.