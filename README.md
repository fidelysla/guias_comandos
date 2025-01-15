# Guias y Comandos

Comandos Basicos

## Virtual Environment

[Virtual Enviroment Creation.](https://github.com/fidelysla/guias_comandos/blob/main/virtual_environment.md)

## Django



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

## GIT

echo "# fastapi-first-step" >> README.md

git init

git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin https://github.com/user/my-project-name.git

git push -u origin main
