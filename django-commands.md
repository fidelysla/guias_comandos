# Django First Steps

## Make a Subdirectory

```CMD
mkdir django-first-step
```

## Make a Virtual Enviroment

[Virtual Enviroment Creation.](https://github.com/fidelysla/guias_comandos/blob/main/virtual_environment.md)

## Python: Select Interpreter

```
ctrl + shift + p
Python 3.10.0 ('.venv':venv) .\.venv\Scripts\python.exe
```

## List PIP (package management system)

```Bash
pip list
```

```CMD
Package    Version
---------- -------
pip        25.0
setuptools 57.4.0
```

```Bash
python -m pip install --upgrade pip
```

## Installing

```
pip install django
```
```
django-admin --version
```
5.1.5

```
$ pip list
Package           Version
----------------- -------
asgiref           3.8.1
Django            5.1.5
pip               25.0
setuptools        57.4.0
sqlparse          0.5.3
typing_extensions 4.12.2
tzdata            2025.1
```

## To Initiate a Project of Django

```
django-admin startproject "first_project_django" .
```

### Run Server

```
python manage.py runserver
```
![Django](https://github.com/user-attachments/assets/adf403da-3cf9-4974-9282-bb260bac8bc4)


pip install mysqlclient

python manage.py startapp "my_app"

* Previamente debe crear la basededatos my_app

* Mysql> CREATE DATABASE my_app;

python manage.py makemigrations

python manage.py migrate
