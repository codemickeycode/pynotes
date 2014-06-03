MySQL
=========
on Ubuntu, install libmysqlclient-dev and python-dev before installing mysql-python on the virtualenv
```
$ sudo apt-get install libmysqlclient-dev
$ sudo apt-get install python-dev
```

```
pip install mysql-python
```

PostgreSQL
=========
```
$ sudo apt-get install postgresql postgresql-contrib
$ sudo -u postgres createdb mydb

$ sudo -u postgres createuser --superuser $USER
$ sudo -u postgres psql

postgres=# \password $USER

$ sudo -u postgres createdb $USER
$ psql

$ sudo apt-get install pgadmin3
$ pgadmin3
```
