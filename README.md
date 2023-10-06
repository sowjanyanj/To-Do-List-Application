# ToDo-list
1) Set up your virtual environment
    python -m venv venv
    source venv/bin/activate
2) Install and test Django
    $python -m pip installdjango=="3.2.9"
3) Create your Django To-Do app
    Scaffold the parent project
      $django-admin startproject todo_project
    Get started onyour Django To-Do list App
      $django-admin startapp todo_app
4) Design Your To-Do Data
      Define Your Data Models
      Create the Database
          (venv) $ python manage.py makemigrations todo_app
          (venv) $ python manage.py migrate
5) Add Your Sample To-Do Data
        Meet the Django Admin Interface
          (venv) $ python manage.py createsuperuser
6) Create and Update Model Objects in Django
7) Use Your Django To-Do List App
