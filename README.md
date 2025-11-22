CRUD OPERATION PROJECT

Technology Used:
- Python
- Django
- HTML, CSS, JavaScript
- SQLite Database
- Git
- PHP
- MySQL

-----------------------------------------
SETUP DJANGO ENVIRONMENT
-----------------------------------------

1. Create virtual environment:
   python3 -m venv env

2. Activate environment:
   Linux/macOS: source env/bin/activate
   Windows: env\Scripts\activate

3. Install Django:
   pip install django

-----------------------------------------
GIT SETUP
-----------------------------------------

4. Initialize git folder:
   git init

-----------------------------------------
DJANGO PROJECT SETUP
-----------------------------------------

5. Create Django project:
   django-admin startproject zedblock

6. Create app:
   python manage.py startapp app

7. Add apps inside settings.py:

   INSTALLED_APPS = [
       'django.contrib.admin',
       'django.contrib.auth',
       'django.contrib.contenttypes',
       'django.contrib.sessions',
       'django.contrib.messages',
       'django.contrib.staticfiles',

       'zedblock',
       'app',
   ]

-----------------------------------------
DATABASE SETUP
-----------------------------------------

8. Create superuser:
   python manage.py createsuperuser

9. Make migrations:
   python manage.py makemigrations

10. Apply migrations:
    python manage.py migrate

-----------------------------------------
FRONTEND SETUP
-----------------------------------------

11. Create templates folder for HTML pages:
    app/templates/

12. Create models inside:
    app/models.py

13. Create CRUD operations inside:
    app/views.py

14. Setup URLs:
    Create app/urls.py and include it in zedblock/urls.py

-----------------------------------------
GIT COMMANDS
-----------------------------------------

15. Add files:
    git add filename1 filename2

16. Commit changes:
    git commit -m "commit message"

17. Check git status:
    git status

-----------------------------------------
RUN PROJECT
-----------------------------------------

18. Start Django server:
    python manage.py runserver
