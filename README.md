Srvup Comments
=====

A reusable Django & Javascript app (jQuery) for simply implementing a comments feed on any url.


Quick start
-----------
1. Install Srvup Comments:

    ```
    pip install srvup-comments
    ```
    

2. Install Django Dependancies:
    - [Django Rest Framework](http://www.django-rest-framework.org/)
    - [Django Cors Headers](https://github.com/ottoyiu/django-cors-headers)
    
    ```
    pip install djangorestframework django-cors-headers
    ```

3. Add "comments" to your INSTALLED_APPS setting like this:

    ```
    INSTALLED_APPS = [
        ...
        'corsheaders', 
        'rest_framework',
        'comments',
    ]
    ```

4. Update Django `settings.py` for [Django Rest Framework](http://www.django-rest-framework.org/) & [Django Cors Headers](https://github.com/ottoyiu/django-cors-headers)


5. Add [jQuery](http://jquery.com/) and [Bootstrap](http://getbootstrap.com/)(optional):
    ```
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>

    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>

    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
    ```

