# cygwin-virtualenv-virtualenvwrapper-
cygwin virtualenv virtualenvwrapper work on windows
This is based on :[Using pip, virtualenv, and virtualenvwrapper in Cygwin](http://anythingsimple.blogspot.com/2010/04/using-pip-virtualenv-and.html)


This is a project make cygwin, virtualenv work together. 

## Install

* Use Cygwin setup to install Python for Cygwin.
* Install easy_install in your Cygwin: download [ez_setup.py](http://peak.telecommunity.com/dist/ez_setup.py) and run ```python .\ez_setup.py``` in Cygwin.
* Install pip by using easy_install: ```eazy_install pip```.
* ```pip install virtualenv```
* ```pip install virtualenvwrapper```
* add the following lines into your ~/.bashrc
```
  export WORKON_HOME=/cygdrive/c/labs/virtualenvs
  source /usr/bin/virtualenvwrapper.sh
```

## Use:

* create a new virtualenv in your Cygwin: ```mkvirtualenv my-first-env```
* activate your virtualenv: ```workon my-first-env``` 
* To deactivate your virtualenv: ```deactivate``` 
* To remove the virtualenv: ```rmvirtualenv my-first-env```



