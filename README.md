# telegram-bot-store
git init git remote add origin https://github.com/ТВОЙ_НИК/telegram-bot-store.git git add . git commit -m "Первый коммит" git push -u origin master # Telegram Bot Store
Простой Telegram-бот для продажи робуксов и гемов. Работает на Aiogram 3 + Render 24/7.services:
  - type: web
    name: telegram-bot-store
    env: python
    buildCommand: pip install -r requirements.txt
    startCommand: python main.py
    envVars:
      - key: BOT_TOKEN
        value: ВСТАВЬ_ТВОЙ_ТОКЕН_ОТСЮДА


