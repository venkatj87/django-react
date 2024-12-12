# django-react
This is a basic Django react project.

# Installation guide for Mac os

Create Django project directory on your computer. Then Naviage to the project directory. Create virtual environment for the project.

Run the following commands:

> `python3 -m venv env`

> `source env/bin/activate`

Create requirement.txt file on the project root directory
add required packages to the requirement.txt file.

> `pip install -r requirement.txt`

Create migrations for any changes on model

`python manage.py makemigrations`

Run migraton

`python manage.py migrate`