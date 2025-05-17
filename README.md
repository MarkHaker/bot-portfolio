# Project Manager Telegram Bot / Менеджер проектов для Telegram 🤖

**English** | **[Русский](#русский)**

---

## Features ✨

- **Project Management**:
  - Add new projects with name, description, URL and status
  - View all your projects at a glance
  - Update project details
  - Delete projects you no longer need

- **Status Tracking**:
  - Set project status (Planning, In Development, Completed, etc.)
  - Update status as project progresses

- **Skills Organization**:
  - Add relevant skills to each project
  - View all skills used across projects

- **User-Friendly Interface**:
  - Interactive menus with buttons
  - Simple step-by-step commands
  - Quick access to project info

## Getting Started 🚀

### Prerequisites
- Python 3.8+
- Telegram account
- `python-telegram-bot` library

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/project-manager-bot.git
   cd project-manager-bot
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up your environment:
   - Rename `config.example.py` to `config.py`
   - Add your Telegram bot token

4. Initialize the database:
   ```bash
   python logic.py
   ```

5. Run the bot:
   ```bash
   python main.py
   ```

## Usage 📋

Start by sending `/start` to your bot. Main commands:

| Command | Description |
|---------|-------------|
| `/new_project` | Add a new project |
| `/projects` | View all projects |
| `/skills` | Add skills to a project |
| `/update_projects` | Modify project details |
| `/delete` | Remove a project |
| `/info` | Show help |

## Database Structure 🗃️

SQLite database with tables:
1. **projects** - Project information
2. **skills** - Available skills
3. **project_skills** - Projects-skills relationship
4. **status** - Project status options

## Contributing 🤝

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add some feature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License 📄
MIT License - see [LICENSE](LICENSE)

## Contact 📧
[Your Name] at [your.email@example.com]

---

# Русский

---

## Возможности ✨

- **Управление проектами**:
  - Добавление проектов с названием, описанием, ссылкой и статусом
  - Просмотр всех проектов
  - Обновление информации
  - Удаление проектов

- **Отслеживание статуса**:
  - Установка статуса (Планирование, В разработке, Завершен и др.)
  - Обновление статуса

- **Организация навыков**:
  - Добавление навыков к проектам
  - Просмотр всех используемых навыков

- **Удобный интерфейс**:
  - Интерактивные меню
  - Простые команды
  - Быстрый доступ к информации

## Начало работы 🚀

### Требования
- Python 3.8+
- Аккаунт в Telegram
- Библиотека `python-telegram-bot`

### Установка

1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/вашusername/project-manager-bot.git
   cd project-manager-bot
   ```

2. Установите зависимости:
   ```bash
   pip install -r requirements.txt
   ```

3. Настройте окружение:
   - Переименуйте `config.example.py` в `config.py`
   - Добавьте токен бота

4. Инициализация БД:
   ```bash
   python logic.py
   ```

5. Запуск бота:
   ```bash
   python main.py
   ```

## Использование 📋

Основные команды:

| Команда | Описание |
|---------|-------------|
| `/new_project` | Добавить проект |
| `/projects` | Просмотр проектов |
| `/skills` | Добавить навыки |
| `/update_projects` | Изменить проект |
| `/delete` | Удалить проект |
| `/info` | Справка |

## Структура БД 🗃️

Таблицы SQLite:
1. **projects** - Информация о проектах
2. **skills** - Навыки
3. **project_skills** - Связи проектов и навыков
4. **status** - Статусы проектов

## Участие в разработке 🤝

1. Форкните репозиторий
2. Создайте ветку (`git checkout -b feature/НоваяФункция`)
3. Зафиксируйте изменения (`git commit -m 'Добавлена функция'`)
4. Отправьте изменения (`git push origin feature/НоваяФункция`)
5. Откройте Pull Request

## Лицензия 📄
MIT - см. [LICENSE](LICENSE)

## Контакты 📧
[Ваше Имя] на [ваш.email@example.com]

---

⭐️ If you like this project, give it a star! / Поставьте звезду, если проект вам понравился! ⭐️
