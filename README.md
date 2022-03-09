# django_books

sudo pip install djangorestframework

sudo django-admin startproject library .

sudo django-admin startapp books

sudo python manage.py runserver

sudo python manage.py migrate


from django.core.management.utils import get_random_secret_key
print(get_random_secret_key())
