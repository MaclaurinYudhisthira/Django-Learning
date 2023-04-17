# Django-Learning

### Check version
> python --version

### Create Env
> python -m venv ./env

### Set execution policy
> Set-ExecutionPolicy Unrestricted -Scope Process

### Activate Virtual environment
> env\Scripts\activate

### List dependencies 
> pip freeze > req.txt

### Django cli
> django-admin help

### Start project
> django-admin startproject btre .

### Folder structure of Project
Project folder has following files:
* \_\_init\_\_.py" : For app to be used as module
* settings.py : For storing the configs of project
* urls.py : For registering url patterns of views of all the apps

### Manage.py help
> python manage.py help

### Run server
> python manage.py runserver

### Start app
> python manage.py pages

### Folder structure of App
App folder has following files:
* \_\_init\_\_.py" : For app to be used as module
* apps.py : For storing the configs of app
* admin.py : For registering models
* models.py : For defining models
* urls.py : For registering url patterns of views
* viwes.py : For defining views
* tests.py : For writing any tests

### After creating App
* Add the app config to INSTALLED_APPS in settings.py of project
* Add the url pattern of app to urlpatterns in urls.py of project