# 🚀 Быстрый старт Telegram API

## ⚡ Быстрая настройка (3 шага)

### 1️⃣ Установка зависимостей
```bash
pip install -r requirements.txt
```

### 2️⃣ Авторизация в Telegram (один раз)
```bash
python auth_telegram.py
```
Введите номер телефона и код из Telegram.

### 3️⃣ Запуск приложения
```bash
python start_telegram_api.py
```

## 🧪 Тестирование

Проверьте работу API:
```bash
python test_telegram_api.py
```

## 📡 API Endpoints

- `GET /api/telegram/channel/giftnews` - посты из канала
- `GET /api/telegram/channel/giftnews/info` - информация о канале
- `GET /api/telegram/channels` - список каналов
- `GET /api/telegram/health` - состояние API

## 🌐 Доступ

- Приложение: http://localhost:8001
- Документация: http://localhost:8001/docs

## 📚 Подробная документация

См. файл `TELEGRAM_API_SETUP.md` для подробной информации.

---

**Готово! 🎉** Ваш Telegram агрегатор новостей работает с полным контентом постов. 