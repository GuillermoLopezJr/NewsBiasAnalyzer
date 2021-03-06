# Heroku Django Starter Template

An utterly fantastic project starter template for Django 1.11.

## Features

- Production-ready configuration for Static Files, Database Settings, Gunicorn, etc.
- Enhancements to Django's static file serving functionality via WhiteNoise.
- Latest Python 3.6 runtime environment. 

## How to Use

To use this project, follow these steps:

1. Create your working environment.
2. Install Django (`$ pip install django`)
3. Create a new project using this template

## Creating Your Project

Using this template to create a new Django app is easy::

    $ django-admin.py startproject --template=https://github.com/heroku/heroku-django-template/archive/master.zip --name=Procfile helloworld

(If this doesn't work on windows, replace `django-admin.py` with `django-admin`)

You can replace ``helloworld`` with your desired project name.

## Deployment to Heroku

    $ git init
    $ git add -A
    $ git commit -m "Initial commit"

    $ heroku create
    $ git push heroku master

    $ heroku run python manage.py migrate

See also, a [ready-made application](https://github.com/heroku/python-getting-started), ready to deploy.

## Using Python 2.7?

Just update `runtime.txt` to `python-2.7.13` (no trailing spaces or newlines!).


## License: MIT

## Further Reading

- [Gunicorn](https://warehouse.python.org/project/gunicorn/)
- [WhiteNoise](https://warehouse.python.org/project/whitenoise/)
- [dj-database-url](https://warehouse.python.org/project/dj-database-url/)





 ,-----.,--.                  ,--. ,---.   ,--.,------.  ,------.
'  .--./|  | ,---. ,--.,--. ,-|  || o   \  |  ||  .-.  \ |  .---'
|  |    |  || .-. ||  ||  |' .-. |`..'  |  |  ||  |  \  :|  `--, 
'  '--'\|  |' '-' ''  ''  '\ `-' | .'  /   |  ||  '--'  /|  `---.
 `-----'`--' `---'  `----'  `---'  `--'    `--'`-------' `------'
----------------------------------------------------------------- 
Welcome to your Django project on Cloud9 IDE!

Your Django project is already fully setup. Just click the “Run” button to start the application. On first run you will be asked to create an admin user. You can access your application from ‘https://news-bias-analyzer-website-guillermo6988.c9users.io/’ and the admin page from 'https://news-bias-analyzer-website-guillermo6988.c9users.io/admin’.

Starting from the Terminal

In case you want to run your Django application from the terminal just run:

Run syncdb command to sync models to database and create Django’s default superuser and auth system

$ python manage.py migrate

Run Django

$ python manage.py runserver $IP:$PORT

Configuration

You can configure your Python version and PYTHONPATH used in Cloud9 > Preferences > Project Settings > Language Support.

Support & Documentation

Django docs can be found at https://www.djangoproject.com/

You may also want to follow the Django tutorial to create your first application: https://docs.djangoproject.com/en/1.9/intro/tutorial01/

Visit http://docs.c9.io for support, or to learn more about using Cloud9 IDE. To watch some training videos, visit http://www.youtube.com/user/c9ide
