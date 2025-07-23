# 📡 API Requests for Telegram Bot

##  1. Проверка доступности Telegram API
**GET** https://api.telegram.org/bot<TOKEN>/getMe  
→ Ожидаемый ответ: 200 OK

---

##  2. Проверка отправки сообщения вручную
**POST** https://api.telegram.org/bot<TOKEN>/sendMessage  
**Body (JSON):**
```json
{
  "chat_id": "<chat_id>",
  "text": "Привет, бот!"
}
