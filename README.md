# Homework_bot


## What can a bot do

• query the Practicum.Homework API every 10 minutes and check the status of the homework submitted for review;

• when the status is updated, analyze the API response and send you a corresponding notification in Telegram;

• log your work and notify you of important issues by sending a message to Telegram.

---

## Technology stack

[![Python](https://img.shields.io/badge/-Python-464646?style=flat-square&logo=Python)](https://www.python.org/)
[![Django](https://img.shields.io/badge/-Django-464646?style=flat-square&logo=Django)](https://www.djangoproject.com/)

## Description of the project

A social network that allows users to create an account, post posts, follow their favorite authors, and tag posts they like.

## Installing the project locally

* Clone repository to local machine:
```bash
git clone https://github.com/Kinin812/Yatube.git
```

* Create and activate virtual environment:

```bash
python -m venv env
```

```bash
source env/bin/activate
```

* Go to directory and install dependencies from requirements.txt file:

```bash
cd youtube/
pip install -r requirements.txt
```

* Perform migrations:

```bash
python manage.py migrate
```

* Start the server:
```bash
python manage.py runserver
```

* The running project is available at: [http://localhost:8000](http://localhost:8000)


