# Task Manager

## 📌 Описание

Task Manager — это веб-приложение на Django с авторизацией, управлением задачами, назначением пользователей, приостановкой и возобновлением задач. Поддержка запуска через Docker.

## ✨ Возможности

- Регистрация и авторизация пользователей
- Создание, редактирование и удаление задач
- Назначение пользователей на задачи
- Приостановка и возобновление задач с комментариями
- Визуальное отображение владельца и участников задачи
- Поддержка PostgreSQL в Docker
- JWT-аутентификация (REST API)

## ⚙️ Стек технологий

- Python 3.10
- Django 5.2
- PostgreSQL
- Docker & Docker Compose
- Bootstrap 5
- Django REST Framework

## 🚀 Установка локально

1. Клонируйте репозиторий:
```bash
git clone <URL>
распакуйте архив
перейдите в каталог
cd task_manager
```

2. Установите зависимости:
```bash
pip install -r requirements.txt
```

3. Выполните миграции и запустите сервер:
```bash
python manage.py migrate
python manage.py createsuperuser  # (по желанию, чтобы попасть в админку)
python manage.py runserver
```

Откройте `http://127.0.0.1:8000` в браузере.

---

## 🐳 Запуск через Docker

1. Убедитесь, что установлен Docker и Docker Compose
2. Выполните команду:
```bash
docker compose up --build
```

Откройте `http://localhost:8000` в браузере.

---

## 📝 Автор

- Создан: 2025-04-10
- Автор: Albert Khuramshin


