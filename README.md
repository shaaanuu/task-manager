# Task Manager

A minimal Django to-do list app.

## Features
- User signup and login
- Create, edit, delete, and view tasks
- Task status: Pending / Completed
- Due date validation
- Dashboard with task counts

## Tech stack
- Django
- SQLite
- HTML/CSS
- Bootstrap

## Setup
```bash
python -m venv .venv
source .venv/bin/activate
pip install django
python manage.py migrate
python manage.py runserver
```

## Layout
- Database: `db.sqlite3`
- Main app: `tasks/`
