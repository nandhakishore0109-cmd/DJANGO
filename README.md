# Student Management System

A web-based Student Management System developed using Python, Django, HTML, CSS, and SQLite. This project helps manage student details and marks through a simple web interface.

## Project Overview

The Student Management System is designed to simplify student record management. Users can add student details, view student records, edit existing information, and manage student marks.

## Technologies Used

- **Frontend:** HTML, CSS
- **Backend:** Python, Django
- **Database:** SQLite
- **Development Tool:** Visual Studio Code
- **Version Control:** Git and GitHub

## Features

- Add student details
- View student records
- Edit student information
- Add and manage student marks
- Store records in an SQLite database
- User-friendly web interface

## Project Structure

```text
DJANGO/
├── manage.py
├── db.sqlite3
├── README.md
├── student/
│   ├── migrations/
│   ├── templates/
│   │   ├── add_marks.html
│   │   ├── add_student.html
│   │   ├── base.html
│   │   ├── edit_student.html
│   │   └── view_student.html
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
└── studentproject/
    ├── settings.py
    ├── urls.py
    ├── asgi.py
    ├── wsgi.py
    └── .gitignore
```

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/nandhakishore0109-cmd/DJANGO.git
```

### 2. Open the project folder

```bash
cd DJANGO
```

### 3. Install Django

```bash
python -m pip install django
```

### 4. Apply database migrations

```bash
python manage.py migrate
```

### 5. Start the development server

```bash
python manage.py runserver
```

### 6. Open the application

Visit the following URL in your browser:

http://127.0.0.1:8000/

## Learning Outcomes

- Understanding Django project structure
- Developing web applications using Python and Django
- Creating HTML templates and styling web pages with CSS
- Working with an SQLite database
- Using Git and GitHub for version control

## Author

**Nandha Kishore Thota**

B.Tech — Electronics and Communication Engineering

## Future Enhancements

- Add authentication and authorization
- Improve form validation and error handling
- Add search and filtering for student records
- Improve the user interface and responsiveness
