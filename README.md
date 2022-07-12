# Homework_bot


# What can a bot do

• query the Practicum.Homework API every 10 minutes and check the status of the homework submitted for review;

• when the status is updated, analyze the API response and send you a corresponding notification in Telegram;

• log your work and notify you of important issues by sending a message to Telegram.

---

## Стек технологий

[![Python](https://img.shields.io/badge/-Python-464646?style=flat-square&logo=Python)](https://www.python.org/)
[![Django](https://img.shields.io/badge/-Django-464646?style=flat-square&logo=Django)](https://www.djangoproject.com/)

## Описание проекта

Социальная сеть, предоставляющая пользователям возможность создать учетную запись, публиковать записи, подписываться на любимых авторов и отмечать понравившиеся записи.

## Установка проекта локально

* Склонировать репозиторий на локальную машину:
```bash
git clone https://github.com/Kinin812/Yatube.git
```

* Cоздать и активировать виртуальное окружение:

```bash
python -m venv env
```

```bash
source env/bin/activate
```

* Перейти в директирию и установить зависимости из файла requirements.txt:

```bash
cd yatube/
pip install -r requirements.txt
```

* Выполните миграции:

```bash
python manage.py migrate
```

* Запустите сервер:
```bash
python manage.py runserver
```

* Запущенный проект доступен по адресу: [http://localhost:8000](http://localhost:8000)
