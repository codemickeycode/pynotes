Install Virtualenv and Virtualenvwrapper
=========
```
pip install virtualenv
pip install virtualenvwrapper
```

Configure Environment Variables
=========
```
export WORKON_HOME=$HOME/.virtualenvs
source /usr/local/bin/virtualenvwrapper.sh
```

Create Virtualenv
=========
```
mkvirtualenv -a ~/Projects/<project name> --no-site-packages <project name>
```