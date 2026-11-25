# Blogicum

Blogicum — учебный Django-проект платформы для публикации постов. Пользователи могут просматривать публикации, знакомиться с отдельными постами, фильтровать записи по категориям и посещать информационные страницы проекта.

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

### 4. Настроить переменные окружения

В корне проекта создайте файл `.env` и добавьте в него:

```env
SECRET_KEY=ваш-секретный-ключ
DEBUG=True
ALLOWED_HOSTS=localhost,127.0.0.1
```

Сгенерировать секретный ключ можно командой:

```bash
python -c "from django.core.management.utils import get_random_secret_key; print(get_random_secret_key())"
```

Вставьте полученный ключ вместо `ваш-секретный-ключ`.

### 5. Выполнить миграции

```bash
python blogicum/manage.py migrate
```

### 6. Запустить сервер

```bash
python blogicum/manage.py runserver
```

Проект будет доступен по адресу http://127.0.0.1:8000/.

## Запуск тестов

Из корневой папки проекта выполните:

```bash
python -m pytest
```

## Лицензия

MIT
