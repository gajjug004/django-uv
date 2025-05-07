# Django project with uv

### Commands to run with uv

```
uv init
uv run
uv add [pakage name]
uv sync
uv sync --no-dev
uv add --group prod guvicorn whitenoise
uv sync --no-group dev --group prod
```

### Run django commands

```
uv run django-admin startproject my-project .
uv run manage.py makemgrations
uv run manage.py migrate
uv run manage.py runserver
```