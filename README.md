Django-webshell
===============
Django application for running python code in your project's environment from django admin.

Installation
------------

    pip install webshell

settings.py:

    INSTALLED_APPS = (
        ...
        'webshell',
        ...
    )

urls.py:

    urlpatterns = patterns('',
        ...
        (r'^admin/webshell/', include('webshell.urls')),
        ...
    )
    
![django-webshell](example.png)
