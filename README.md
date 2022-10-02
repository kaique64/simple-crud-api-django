# Django REST Framework CRUD API

## What are the requirements to run this application?
- Python (3.6, 3.7, 3.8, 3.9, 3.10)
- Django (2.2, 3.0, 3.1, 3.2, 4.0, 4.1)
- pip

## How can I run this application?
- First step, is create the virtual environment
```sh
python -m venv venv
```
- Second step, is activate the virtual environment (this will works on Windows):
```sh
.\venv\Scripts\Activate.ps1
```
- After that, install all the required libs:
```sh
pip install -r requirements.txt
```
- Now, we gonna create the SQLite database file, called ``db.sqlite3``
- At this point, we need to run the database migrations:
```sh
# Create database migrations
python manage.py makemigrations

# Run the migrations on database
python manage.py migrate
```
- Finally, you can run the server with the command below and have fun:
```sh
python manage.py runserver
```