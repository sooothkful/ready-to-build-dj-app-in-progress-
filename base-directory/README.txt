
#example README.txt from https://docs.djangoproject.com/en/3.1/into/reusable-apps/

=====
Base
=====

Base is a Django app.......

Put description of app here...

Quick start
-----------

1. Add "base" to your INSTALLED_APPS setting like this::

    INSTALLED_APPS = [
        ...
        'base',
    ]

2. Include the polls URLconf in your project urls.py like this::

    path('polls/', include('base.urls')),

3. Run ``python manage.py migrate`` to create the base models.

4. Start the development server and visit http://127.0.0.1:8000/admin/
