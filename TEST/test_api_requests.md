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
  "text": "Привет из Postman!"
}

---

## 3. Проверка отправки сообщения в режиме Polling
**POST** https://api.telegram.org/bot<TOKEN>/getUpdates  
**Body (JSON):**
```json
{
  "chat_id": "<chat_id>",
  "text": "Привет из Postman!"
}

---

##  4. Проверка отправки сообщения вручную
**POST** https://api.telegram.org/bot<TOKEN>/getWebhookInfo 
→ Ожидаемый ответ: 200 OK
