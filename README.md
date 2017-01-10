[![Stories in Ready](https://badge.waffle.io/qliu/di_geocoding.png?label=ready&title=Ready)](https://waffle.io/qliu/di_geocoding)
# Data Initiative Online Geocoding Tool

##The Geocoding tool is a project of Gary Community Investments 
###with colaborartion fro Code for Denver.

The tool is designed to allow for quick and simple uploading and mapping of data in various formats.
This repo in particular holds the source code with advanced front end templates that Code for Denver has worked on.

The project is built in Python using the [Django](https://www.djangoproject.com/) web framework. Developers should have some familiarity before diving in (see [the tutorial](https://docs.djangoproject.com/en/1.10/intro/tutorial01/))


##Getting started


1. git clone this repo

2. install [postgres](https://www.postgresql.org/download/) and create a database for this project. 
make sure python - pycopg2 is installed - 
`sudo apt-get install python-psycopg2`

3. (optional) cd into the repo and create a virtual environment and install the dependencies. 

(these commands are for bash, for windows checkout [virtualenv-win](https://github.com/davidmarble/virtualenvwrapper-win))

`pip install virtualenv`
`pip install virtualenvwrapper`
`mkvirtualenv -a [paste current path again] -r requirements.txt geocode`

activate the virtual environment via 
`workon geocode`

4. to insure the right libraries are installed, run
`pip install -r requirements.txt`

5. start the app with `python manage.py runserver`. to see other app management commands simply run `python mange.py`