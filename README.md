🚀 Социальный рейтинг бот для Telegram с фермой и животными

English | Русский

---

🇷🇺 Русский

📖 Описание

Многофункциональный Telegram бот с системой социального рейтинга, фермой, коллекционированием животных и полной админ-панелью. Идеально подходит для создания игрового сообщества в Telegram!

✨ Возможности

· ⭐️ Система рейтинга — зарабатывайте очки за активность
· 🌾 Ферма — покупайте и коллекционируйте животных
· 🐷 Животные — 3 вида с разной редкостью (обычная, необычная, редкая, эпическая, мифическая)
· 💰 Экономика — собирайте доход, обменивайте валюту на рейтинг
· 🏆 Достижения — получайте награды за коллекционирование
· 👑 Админ-панель — полное управление ботом
· ⚖️ Наказания — система правил и штрафов
· 🚫 Блокировка — возможность блокировать пользователей
· 📊 Статистика — отслеживайте активность пользователей
· 📧 Email отчеты — получайте статистику на почту

🛠 Технологии

· Python 3.9+
· python-telegram-bot
· asyncio
· JSON для хранения данных

📋 Требования

· Python 3.9 или выше
· Токен бота от @BotFather
· Хостинг с поддержкой Python (PythonAnywhere, Railway, Render и т.д.)

🚀 Быстрый старт

1. Клонирование репозитория

```bash
git clone https://github.com/yourusername/social-rating-bot.git
cd social-rating-bot
```

2. Создание виртуального окружения

```bash
python -m venv venv
source venv/bin/activate  # для Linux/Mac
# или
venv\Scripts\activate  # для Windows
```

3. Установка зависимостей

```bash
pip install -r requirements.txt
```

4. Настройка переменных окружения

Создайте файл .env в корневой папке:

```env
# Обязательные параметры
BOT_TOKEN=your_bot_token_here
ADMIN_IDS=111111,222222,333333

# Опционально (для email отчетов)
SENDER_EMAIL=your_email@gmail.com
SENDER_PASSWORD=your_app_password
RECIPIENT_EMAIL=admin@example.com
SMTP_SERVER=smtp.gmail.com
SMTP_PORT=587
```

5. Запуск бота

```bash
python bot.py
```

📦 Зависимости

Создайте файл requirements.txt:

```
python-telegram-bot==13.15
python-dotenv==1.0.0
```

🌐 Деплой на хостинг

Вариант 1: PythonAnywhere (бесплатно)

1. Зарегистрируйтесь на pythonanywhere.com
2. Откройте консоль Bash
3. Клонируйте репозиторий:

```bash
git clone https://github.com/yourusername/social-rating-bot.git
cd social-rating-bot
```

1. Создайте виртуальное окружение:

```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

1. Настройте переменные окружения в разделе Web → Environment variables
2. Запустите бота:

```bash
python bot.py
```

Вариант 2: Render.com

1. Зарегистрируйтесь на render.com
2. Создайте новый Background Worker
3. Подключите ваш GitHub репозиторий
4. Укажите команды:
   · Build Command: pip install -r requirements.txt
   · Start Command: python bot.py
5. Добавьте переменные окружения в разделе Environment
6. Нажмите "Create Worker"

🔧 Настройка команд в BotFather

1. Откройте @BotFather
2. Отправьте /setcommands
3. Выберите вашего бота
4. Отправьте:

```
start - 🚀 Запустить бота / Главное меню
menu - 📋 Открыть главное меню
rating - ⭐️ Показать мой рейтинг
farm - 🌾 Открыть ферму
daily - 🎁 Получить ежедневный бонус
achievements - 🏆 Мои достижения
inventory - 📦 Инвентарь с животными
```

📁 Структура файлов

```
social-rating-bot/
├── bot.py              # Основной код бота
├── requirements.txt    # Зависимости
├── .env               # Переменные окружения (не в Git)
├── .gitignore         # Игнорируемые файлы
├── README.md          # Документация
├── animals.json       # Данные о животных (создается автоматически)
├── achievements.json  # Достижения (создается автоматически)
├── banned_users.json  # Заблокированные пользователи
├── punishments.json   # История наказаний
└── custom_rules.json  # Пользовательские правила
```

🔒 Безопасность

· Все чувствительные данные хранятся в переменных окружения
· Токен бота не попадает в код
· Пароли не видны в репозитории
· Используйте .gitignore для защиты файлов

Пример .gitignore:

```
.env
*.json
__pycache__/
venv/
*.pyc
```

🤝 Вклад в проект

1. Форкните репозиторий
2. Создайте ветку для фичи (git checkout -b feature/amazing-feature)
3. Зафиксируйте изменения (git commit -m 'Add amazing feature')
4. Отправьте в ветку (git push origin feature/amazing-feature)
5. Откройте Pull Request

📄 Лицензия

MIT License

---

🇬🇧 English

📖 Description

Multifunctional Telegram bot with social rating system, farm, animal collection and full admin panel. Perfect for creating a gaming community in Telegram!

✨ Features

· ⭐️ Rating system — earn points for activity
· 🌾 Farm — buy and collect animals
· 🐷 Animals — 3 types with different rarity (common, uncommon, rare, epic, mythical)
· 💰 Economy — collect income, exchange currency for rating
· 🏆 Achievements — get rewards for collecting
· 👑 Admin panel — full bot management
· ⚖️ Punishments — rules and fines system
· 🚫 Ban system — ability to block users
· 📊 Statistics — track user activity
· 📧 Email reports — receive statistics by email

🛠 Technologies

· Python 3.9+
· python-telegram-bot
· asyncio
· JSON for data storage

📋 Requirements

· Python 3.9 or higher
· Bot token from @BotFather
· Hosting with Python support (PythonAnywhere, Railway, Render, etc.)

🚀 Quick Start

1. Clone repository

```bash
git clone https://github.com/yourusername/social-rating-bot.git
cd social-rating-bot
```

2. Create virtual environment

```bash
python -m venv venv
source venv/bin/activate  # for Linux/Mac
# or
venv\Scripts\activate  # for Windows
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

4. Configure environment variables

Create .env file in the root folder:

```env
# Required parameters
BOT_TOKEN=your_bot_token_here
ADMIN_IDS=111111,222222,333333

# Optional (for email reports)
SENDER_EMAIL=your_email@gmail.com
SENDER_PASSWORD=your_app_password
RECIPIENT_EMAIL=admin@example.com
SMTP_SERVER=smtp.gmail.com
SMTP_PORT=587
```

5. Run the bot

```bash
python bot.py
```

📦 Dependencies

Create requirements.txt:

```
python-telegram-bot==13.15
python-dotenv==1.0.0
```

🌐 Hosting Deployment

Option 1: PythonAnywhere (free)

1. Register at pythonanywhere.com
2. Open Bash console
3. Clone repository:

```bash
git clone https://github.com/yourusername/social-rating-bot.git
cd social-rating-bot
```

1. Create virtual environment:

```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

1. Configure environment variables in Web → Environment variables
2. Run the bot:

```bash
python bot.py
```

Option 2: Render.com

1. Register at render.com
2. Create new Background Worker
3. Connect your GitHub repository
4. Set commands:
   · Build Command: pip install -r requirements.txt
   · Start Command: python bot.py
5. Add environment variables in Environment section
6. Click "Create Worker"

🔒 Security

· All sensitive data stored in environment variables
· Bot token never appears in code
· Passwords are not visible in repository
· Use .gitignore to protect files

Example .gitignore:

```
.env
*.json
__pycache__/
venv/
*.pyc
```

---

📄 License

MIT License
