# django_env

On windows

1. Create virtual env
2. python -m venv ecom_env
3. cd ecom_env
4. Run activate: ecom_env\Scripts>activate
5. Deactivate: deactivate

On Linux

source ecom_env/bin/activate

# Install django
https://docs.djangoproject.com/en/4.2/intro/install/
https://docs.djangoproject.com/en/4.2/topics/install/#installing-official-release
1. Run virtual env
2. pip install django
# Verifying

To verify that Django can be seen by Python, type python from your shell. Then at the Python prompt, try to import Django:

>>> import django
>>> print(django.get_version())
4.2

4. Create a prj in django: django-admin startproject name_prj .
5. Run: python manage.py runserver
6. Create a app in django: python manage.py startapp name_app

# Setup database
