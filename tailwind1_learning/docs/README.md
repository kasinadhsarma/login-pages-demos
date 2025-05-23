# Django Project Structure

This repository contains a Django-based web application with TailwindCSS integration.

## Previous Structure (React/Next.js)
For reference, our previous project structure for React/Next.js applications was:

```
file system 
    |-- docs/
    |-- backend/
    |-- frontend or src/
    |-- README.md
    |-- index.html
    |-- .gitignore
```

## Current Django Project Structure
The current project follows Django's recommended structure:

```
file system
    |-- core/                 # Django app containing main functionality
        |-- migrations/
        |-- admin.py
        |-- apps.py
        |-- models.py
        |-- tests.py
        |-- views.py
    |-- docs/                 # Project documentation
        |-- README.md
        |-- Goals/
    |-- myproject/           # Django project settings
        |-- settings.py
        |-- urls.py
        |-- wsgi.py
        |-- asgi.py
    |-- static/              # Static files
        |-- css/
        |-- images/
        |-- js/
    |-- templates/           # HTML templates
    |-- manage.py           # Django management script
    |-- db.sqlite3         # SQLite database
## Getting Started

To set up and run the project:

```bash
# Create a new Django project (replace <project_name> with your desired name)
django-admin startproject <project_name>

# Navigate into the project directory
cd <project_name>

# Start the development server
python3 manage.py runserver
```
this is backend now  i am forwording until till now now i am doing frontend part date ( friday may 23 11:39:20p.m)