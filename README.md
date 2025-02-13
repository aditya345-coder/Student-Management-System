# Student Management System

This is a student management system built using **Django 4**, **HTML 5**, **CSS 3**, and **Bootstrap 5** with a **Bootswatch** theme.

## Table of Contents 
- [Installation](#installation)
- [Run the application](#run-the-application)
- [Run the tests](#run-the-tests)
- [View the application](#view-the-application)

## Folder Structure
```
D:.
├───.github
│   └───workflows
├───django_project
│   └─── __init__.py
│   └─── asgi.py
│   └─── settings.py
│   └─── urls.py
│   └─── wsgi.py
│ 
└───students
    ├───migrations
    ├───static
    │   ├───css
    │   └───images
    └───templates
    │   └───students
    └─── __init__.py
    └─── admin.py
    └─── apps.py
    └─── forms.py
    └─── models.py
    └─── tests.py
    └─── urls.py
    └─── views.py
```

## Installation

### 1. Create a virtual environment

From the **root** directory, run:

```bash
python -m venv venv
```

### 2. Activate the virtual environment

From the **root** directory, run:

On Windows:

```bash
venv\scripts\activate
```

### 3. Install required dependencies

From the **root** directory, run:

```bash
pip install -r requirements.txt
```

### 4. Run migrations

From the **root** directory, run:

```bash
python manage.py makemigrations
```
```bash
python manage.py migrate
```

### 5. Create an admin user to access the Django Admin interface

From the **root** directory, run:

```bash
python manage.py createsuperuser
```

When prompted, enter a username, email, and password.

## Run the application

From the **root** directory, run:

```bash
python manage.py runserver
```

## Run the tests

From the **root** directory, run:

```bash
python manage.py test --pattern="tests.py"

```

## View the application

Go to http://127.0.0.1:8000/ to view the application.


