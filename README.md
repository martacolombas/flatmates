# flatmates
An app that makes finding the perfect apartment a collaborative experience

> This step is skippable if you already have a python virtual environment manager

### HOW TO INSTALL VIRTUALENVWRAPPER

If you don't have virtualenvwrapper, make sure you have it installed before running this project

```
pip install virtualenvwrapper
```

This command lets you know where the file is located.

```
which virtualenvwrapper.sh
```

Copy paste the path into the shell's config file (in my case `.zshrc`)

```
export WORKON_HOME=$HOME/.virtualenvs
source /usr/local/bin/virtualenvwrapper.sh
```

update your terminal settings

```
source ~/.zshrc
```

You're ready to run the `virtualenvwrapper` commands

```
workon
deactivate
mkvirtualenv
cdvirtualenv
rmvirtualenv
```

### HOW TO RUN THIS PROJECT LOCALLY

1. Clone this project into your local folder
2. Make a virtual environment using python 3

```
 mkvirtualenv --python=/usr/bin/python3 nameOfEnvironment
```

3. Activate environment

```
 workon nameOfEnvironment
```

4. Install Django in your virtual environment

```
pip install -r requirements.txt
```

5. Run python server

```
python manage.py runserver
```

