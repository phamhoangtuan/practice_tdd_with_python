Practice TDD with Python 3

Reference book: Test-Driven Development with Python, 2nd edition (https://www.obeythetestinggoat.com/)

Create a python virtual environment: 
- virtualenv -p python3 .venv

Activate virtual environment: 
- source .venv/bin/activate

Install packages: 
- pip install -r requirements.txt

Start django server:
- python manage.py runserver

Run the functional tests:
- python functional_tests.py

Run the unit tests:
- python manage.py test

Migrate database:
- python manage.py makemigrations
- python manage.py migrate
