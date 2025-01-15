# FastAPI First Steps

## Previously

[Virtual Enviroment Creation.](https://github.com/fidelysla/guias_comandos/blob/main/virtual_environment.md)

## Installing

	pip install fastapi uvicorn

## Python: Select Interpreter

	ctrl + shift + p
 	Python 3.10.0 ('.venv':venv) .\.venv\Scripts\python.exe

## Make file `main.py`

```
from fastapi import FastAPI

app = FastAPI()

@app.get('/')
def home():
    return "Hola Mundo"
```

## Run
```
uvicorn main:app
```
```
uvicorn main:app --reload
```
```
uvicorn main:app --port 5000
```
```
uvicorn main:app --host 0.0.0.0
```
```
uvicorn main:app --host 0.0.0.0 --port 5000 --reload
```
	
