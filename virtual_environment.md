# Virtual Environment

## Setup with Python:

  	py -3 -m venv .venv

## Setup with UV Package Manager

	pip install uv

```
uv init
uv venv
source .venv/Scripts/activate
```


## Activate

cmd.exe:
 	
	.venv\Scripts\activate.bat

PowerShell:

> `Get-ExecutionPolicy`
> 
> * Restricted: No permite ejecutar ningún script (es la causa de tu problema).
> * RemoteSigned: Permite ejecutar scripts locales, pero los descargados de Internet deben estar firmados.
> * Unrestricted: Permite ejecutar todos los scripts (menos seguro).
>
> `Set-ExecutionPolicy RemoteSigned`
>
> `Set-ExecutionPolicy Restricted`
 
	.venv\Scripts\activate.ps1

Bash:

 	source .venv/Scripts/activate

## Deactivate

	deactivate

