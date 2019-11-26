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

## References

- [Python 最佳实践指南！](https://pythonguidecn.readthedocs.io/zh/latest/)
- [Using Python environments in VS Code](https://code.visualstudio.com/docs/python/environments)
