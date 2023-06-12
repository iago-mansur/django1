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

editar settings.py

editar urls.py

criar core.urls.py

editar views.py

criar templates

criar .html

editar model

python manage.py makemigrations && python manage.py migrate

python manage.py createsuperuser

admin / email@email.com / 123456 / y

editar admin.py
