# curd-operation
#use python
#use django
#use in html,css javascript
#sqlite database
#use in git
#php
#mysql
#setup django evviorment for running project
python3 -m venv env
#install django
pip install django
#make a git folder
git init folder name

#make a project
django-admin startproject zedblock

#make a app
python manage.py startapp app

#go in setting.py and setup in
installed [
'zedblock',
'app',
]

#create a superuser
python manage.py createsuperuser

#setup database migrations
python manage.py makemigrations

after migrate
python manage.py migrate

#create a templates for html page
#create models for database orm

setup url and write operations in views.py 

after add some file in git 

git add file name second filename

git commit (changes)

after check git status

and after run the run command

python manage.py runserver


