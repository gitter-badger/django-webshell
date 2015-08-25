Django-webshell
===============

[![Join the chat at https://gitter.im/Krukov/django-webshell](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/Krukov/django-webshell?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
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
