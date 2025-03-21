#MaglangitRosepel_MidtermProject
#Instructions_on_how_to_setup_django_project
1. python --version
2. pip --version
3. pip install virtualenv
4. virtualenv venv
5. venv\Scripts\activate
6. source venv/bin/activate
7. pip install django
8. django-admin startproject myproject
9. cd myproject
10. python manage.py runserver
11. python manage.py startapp myapp
12. INSTALLED_APPS = [
    # other apps
    'myapp',
]
13. python manage.py migrate
14. python manage.py createsuperuser
15. python manage.py runserver
16. 
