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

=================================================================
python manage.py shell

from core.models import Produto

dir(Produto)

produtos = Produto.objects.all()

for produto in produtos:
    print(produto)

Produto.objects.count()

Produto.objects.last()

Produto.objects.firt()

Produto.objects.filter(id=1)
=================================================================

criar pasta static

criar pastas: css, js, images

crair arquivos html, js e imagens.

python manage.py collectstatic

pip install whitenoise gunicorn

criar runtime.txt

criar Procfile

pip freeze > requirements.txt

criar .gitignore

git init

git add .

git config user.email "seuemail@email.com"

git config user.name  "seu user"

git commit -m "Projeto finalizado"

cadastrar heroku

sudo snap install heroku --classic

heroku login

heroku create dominio --buildpack heroku/python

git push heroku master

heroku logs --tail