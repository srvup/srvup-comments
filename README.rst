=====
Srvup Comments
=====

Comming Soon

Quick start
-----------
1. Install Dep:
    pip install djangorestframework django-cors-headers

2. Add "comments" to your INSTALLED_APPS setting like this::

    INSTALLED_APPS = [
        ...
        'corsheaders', # https://github.com/ottoyiu/django-cors-headers
        'rest_framework', # http://www.django-rest-framework.org/
        'comments',
    ]
