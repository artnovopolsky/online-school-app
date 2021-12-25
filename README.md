# Welcome to Online School App!

Реализовано приложение для онлайн-школы. Приложение базируется на фреймворке `Django`.

## Features

* **Регистрация и авторизация** для нескольких типов пользователей *с разными уровнями доступа* (преподаватель, студент, ментор)
* **Манипуляция данными** (например, преподаватель может ставить/изменять оценки студентам, добавлять/удалять уроки)
* **Фильтрация данных** для всех сущностей (например, можем отфильтровать курс по стоимости/длительности/названию)

## Getting started

Ничего хитрого:

```
git clone https://github.com/artnovopolsky/online-school-app.git
cd online-school-app
pip install -r requirements.txt
cd onlineschool
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

Приложение будет доступно локально по адресу http://127.0.0.1:8000/. Админка - по адресу http://127.0.0.1:8000/admin.

## Documentation

Более подробно ознакомиться с интерфейсом и функциями приложения можно [здесь](https://github.com/artnovopolsky/online-school-app/blob/main/docs/docs.pdf).
