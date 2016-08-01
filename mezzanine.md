# Install from PyPI
$ pip install mezzanine==4.0.1

# Create a project
```
$ mezzanine-project myproject
$ cd myproject
```

# Create a database
```
$ python manage.py createdb
```

# Run the web server
```
$ python manage.py runserver
```

```
$ python manage.py collecttemplates
```
https://github.com/stephenmcd/mezzanine/issues/1512

https://www.pythonanywhere.com/forums/topic/1195/

TEMPLATE_DIRS = [TEMPLATES[0]['DIRS'][0]]