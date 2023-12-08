# Basic commands

To ensure proper installation of python

```
python --version
# or
python3 --version
```

Create a virtual environment in the project's root

```
virtualenv <venv_name>
# or
python3 -m venv <venv_name>
```

Activate virtual environment in the project root

```
source <venv_name>/bin/activate     # linux based system

<venv_name>\Scripts\activate        # Windows
```

Install dependencies

```
pip install -r requirements.txt
```

List all dependencies for the current project

```
pip freeze
```

Create requirements.txt for the current project

```
pip freeze > requirements.txt
```

Execute any .py files

```
python <app_name>.py
# or
python3 <app_name>.py
```

Run Django App

```
python manage.py runserver
```

Run Django App on a specific port

```
python manage.py runserver 0.0.0.0:<port_number>
```

Run Flask App

```
flask run
```

Run Flask App on a specific port

```
flask run --host=0.0.0.0 --port=<port_number>
```

Run fastAPI

```
uvicorn <app_name>:<app_instance_name>
```

Run fastAPI on a specific port

```
uvicorn <app_name>:<app_instance_name> --host 0.0.0.0 --port <port_number>
```
