# weather-webapp-django
This is a weather web application developed using Django

Snapshot : 

![main page](https://github.com/thedevsafaf/weather-webapp-django/assets/85129653/ddeb94f5-cf51-48ff-8e4e-6ee05c1956d0)


First clone the repository from Github and switch to the new directory:

$ git clone git@github.com/USERNAME/<project_name>.git

$ cd <project_name>

Setup the project structure:
```
-sample (project folder)
        -src
              -sample (project name)
                      -sample (main app name)
                              -settings.py
                              -urls.py
                              -wsgi.py
                       -app1
                       -app2
                       -appn
                       -requirements.txt
                       -manage.py      
        -venv  
```
Activate the virtualenv for your project.

PROJECT CONFIGURATION if first time
========================================
install virtualenv first
```
pip install --user virtualenv 
```
create virtual environment named venv
```
python -m virtualenv venv
```
activate the venv using activate script
```
venv\Scripts\activate
```
install django in the same venv
```
pip install django
```
to see the installed packages
```
pip freeze
```
install the driver for interacting with PostgreSQL from the Python scripting language
```
pip install psycopg2
```
install postgres for the first time or use sqlite by default
```
depends on the OS

 setup postgres sql
 setup server, username, password, port no. etc
 create database
```
Install project dependencies:
```
$ pip install -r requirements/local.txt
```
Then simply apply the migrations:
```
$ python manage.py migrate
```
You can now run the development server:
```
$ python manage.py runserver
```
