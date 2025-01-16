# Flet First Steps

## Previously

[Virtual Enviroment Creation.](https://github.com/fidelysla/guias_comandos/blob/main/virtual_environment.md)

## Installing

```
pip install flet
```
```
flet --version
```

## Create a new Flet app

```
flet create my_flet_app
```

> To create your Flet app in current directory.
```
flet create .
```

## Running Flet app

> This command will run `main.py` located in `my_flet_app` directory.
```
flet run my_flet_app
```

> To run your Flet app in current directory.
```
flet run
```

> If you need to provide a different path to the file, use the following command:
```
flet run [script]
```

> To run `main.py` located in a different directory, provide an absolute or a relative path to the directory where it is located, for example:

```
flet run /Users/JohnSmith/Documents/projects/flet-app
```

> To run script with a name other than `main.py`, provide an absolute or a relative path to the file, for example:

```
flet run counter.py
```

```
flet run my_other_app/counter.py
```

## Run as a web app

```
flet run --web [script]
```
```
flet run --web --port 8000 app.py
```

## Hot reload

```
poetry run flet run -d [script]
```
```
poetry run flet run -d -r [script]
```

