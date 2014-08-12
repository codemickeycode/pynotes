Useful django commands
===========
## Creating the models
```
$ ./manage.py syncdb
$ ./manage.py makemigrations
$ ./manage.py migrate
```
shortcut
```
$ ./manage.py syncdb --migrate
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
