Install pip
===========
```
$ sudo easy_install pip
```

Install Virtualenv and Virtualenvwrapper
=========
```
$ sudo pip install virtualenv
$ sudo pip install virtualenvwrapper
```

Configure Environment Variables and Reload bashrc
=========
```
$ echo "WORKON_HOME=~/.envs" >> ~/.bashrc
$ echo "PROJECT_HOME=~/Projects" >> ~/.bashrc
$ echo "source /usr/local/bin/virtualenvwrapper.sh" >> ~/.bashrc

$ source ~/.bashrc
```

Create Virtualenv
=========
```
mkvirtualenv -a ~/Projects/<project name> --no-site-packages <project name>
```

OR specify python version
```
mkvirtualenv -p /usr/bin/python3 -a ~/Projects/<project name> --no-site-packages <project name>
```
