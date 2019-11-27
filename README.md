# django-codelab

Learning Django and Python by examples

## Install Dependencies

freeze your requirements

```bash
pip3 freeze > requirements.txt
```

install dependencies from `requirements.txt` file

```bash
pip3 install -r requirements.txt
```

## Usage

activate virtual environment:

```bash
source ./venv/bin/activate
```

Run server

```bash
python manage.py runserver
```

django shell mode:

```bash
python manage.py shell
```

## Test

```bash
python manage.py test
```

## Admin users

username: admin
email: admin@example.com
password: codelabpass

## Reusable apps

Build `polls` application package

```bash
cd django-polls
python setup.py sdist
```

Install `django-polls` application package into `django-codelab`

```bash
cd django-codelab
pip3 install django-polls/dist/django-polls-0.1.tar.gz
```

Uninstall `django-polls` application package from `django-codelab`

```bash
pip3 uninstall django-polls
```

## References

- [Python 最佳实践指南！](https://pythonguidecn.readthedocs.io/zh/latest/)
- [Using Python environments in VS Code](https://code.visualstudio.com/docs/python/environments)
