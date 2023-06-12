mkdir django1

cd django1

code .

python3 -m venv .venv

. .venv/bin/activate

pip install django

pip freeze > requirements.txt

django-admin startproject django1 .

django-admin startapp core

python manage.py runserver