Useful django 1.7 commands
===========
## Creating the models
```
$ ./manage.py syncdb
$ ./manage.py makemigrations
$ ./manage.py migrate
```

## Start an app and project
```
$ django-admin.py startproject <project name>

$ cd <project dir>
$ django-admin.py startapp <app name>
```

## Run the dev server
```
$ ./manage.py runserver
```

## Collect static files
```
$ python manage.py collectstatic
```

## Create Django Admin Superuser
```
$ python manage.py createsuperuser --username=<username> --email=<you@example.com>
```
