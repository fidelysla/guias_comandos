py -m venv .venv

pip list

pip install django

django-admin startproject "my_project_name" .

pip install mysqlclient

python manage.py runserver

python manage.py startapp "my_app"

* Previamente debe crear la basededatos my_app

* Mysql> CREATE DATABASE my_app;

python manage.py makemigrations

python manage.py migrate
