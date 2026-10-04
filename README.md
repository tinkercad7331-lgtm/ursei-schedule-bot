# Telegram-бот расписания

## Локальный запуск
1. Установи Python 3.11+.
2. `pip install -r requirements.txt`
3. В Windows:
   `set BOT_TOKEN=ТОКЕН_ОТ_BOTFATHER`
   `set WEBHOOK_URL=http://localhost:10000`
4. `python bot.py`

## Бесплатный Render
1. Создай GitHub-репозиторий и загрузи эти 3 файла.
2. На Render создай Web Service из репозитория.
3. Build Command: `pip install -r requirements.txt`
4. Start Command: `python bot.py`
5. Добавь переменные:
   BOT_TOKEN = токен от BotFather
   WEBHOOK_URL = адрес Render-сервиса, например https://schedule-bot-xxxx.onrender.com
6. После деплоя Telegram будет отправлять обновления на webhook.

Важно: не публикуй BOT_TOKEN в GitHub и никому его не отправляй.
