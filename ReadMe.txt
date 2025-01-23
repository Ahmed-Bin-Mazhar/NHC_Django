# Django-Tutorial
 Demo Project (CRUD)


Creating V-ENV

Step 1 Install Python3 
Step 2 Create a virtual env "python -m venv .venv"
Step 3 Open the project file
Step 4 Activate env ".venv\Scripts\activate"

Installations

Step 1 pip install django
Step 2 pip install djangorestframework
Step 3 django-admin // can see commands 
Step 4 django-admin startproject drinks .  // creates a django project
Step 5 python manage.py runserver
Step 6 python manage.py migrate // will apply all the migrations
Step 6 Goto http://127.0.0.1:8000/admin/login/?next=/admin/
Step 7 python manage.py createsuperuser
    username: ahmed
    email: ahmed@ahmed.com
    password: ahmed
    it will ask to bypass password validation say yes 

Step 8 create a file models.py inside project drictory 



Creating model

1. Goto settings.py, look for INSTALLED_APPS in this add the project drinks
2. python manage.py makemigrations drinks
3. python manage.py //will apply all migrations 
4. create a file in project directory admin.py



Start Rest framework 

1. Goto Settings.py, goto installed_apps and write 'rest_framework', 
2. Create a file serializers.py in project directory // this will convert a python object into a JSON object 
3. cretae views.py in project directory to create endpoints 



