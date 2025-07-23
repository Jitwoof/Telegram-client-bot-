# Telegram FAQ Bot (Python + Flask + Telegram API)
Бот принимает команды от пользователей Telegram, предлагает заполнить анкету для подбора продукта, а также получить ответы на часто задаваемые вопросы (FAQ). Работает через webhook, задеплоен на PythonAnywhere.

# СТЕК
- Python 3.13
- Flask
- python-telegram-bot v20+
- PostgreSQL / MySQL (через phpMyAdmin)
- PythonAnywhere (хостинг)
- Postman (тестирование API)

## 🚀 Возможности
- Команда `/start` и интерактивное меню
- Сбор контактной информации через форму
- FAQ: быстрые ответы на часто задаваемые вопросы
- Запись сообщений в БД
- Поддержка webhook (реакция на входящие от Telegram)

## 📷 Скриншоты
![Webhook OK](static/webhook_ok.png)
![DB](static/database_feedback.png)

## ✅ API-тесты
См. [test/test_api_requests.md](test/test_api_requests.md)

## 📎 Полезное
- [Webhook setup](webhook_setup.md)
- [Архитектура](docs/architecture.md)
- [Инструкция по деплою](docs/deployment_steps.md)
