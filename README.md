# Blogicum

Blogger — учебный Django-проект платформы для публикации постов. Пользователи могут просматривать публикации, знакомиться с постами, фильтровать записи по категориям и посещать информационные страницы проекта.

## Возможности

- Просмотр ленты публикаций.
- Просмотр отдельных постов.
- Фильтрация публикаций по категориям.
- Информационные страницы «О проекте» и «Правила».

## Стек технологий

- Python
- Django
- HTML
- CSS
- SQLite

## Запуск проекта локально

### 1. Клонировать репозиторий

```bash
git clone https://github.com/FanisNK/django-sprint1-main.git
cd django-sprint1-main
```

### 2. Создать виртуальное окружение

```bash
python -m venv venv
```

Активировать окружение:

**macOS / Linux**
```bash
source venv/bin/activate
```

**Windows**
```bash
venv\Scripts\activate
```

### 3. Установить зависимости

```bash
pip install -r requirements.txt
```

### 4. Выполнить миграции

```bash
python manage.py migrate
```

### 5. Запустить сервер

```bash
python manage.py runserver
```

Проект будет доступен по адресу http://127.0.0.1:8000/.

## Лицензия

MIT
