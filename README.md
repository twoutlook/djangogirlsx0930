https://tutorial.djangogirls.org/en/

    sudo apt install python3.5 python3.5-venv
    
    python3.5 -m venv myvenv
    source myvenv/bin/activate
    
    pip install django
    pip install --upgrade pip
    
https://tutorial.djangogirls.org/en/intro_to_command_line/
    whoami
    pwd
    ls
    ll
  
# Python
https://tutorial.djangogirls.org/en/python_installation/  
    
    (myvenv) twoutlook:~/workspace/djangogirls $ python --version
    Python 3.5.2
    
# Django    
https://tutorial.djangogirls.org/en/django_installation/ 

    django-admin startproject mysite

settings.py
    TIME_ZONE = 'Asia/Taipei'
    STATIC_ROOT = os.path.join(BASE_DIR, 'static')
    
    python manage.py migrate
    python manage.py runserver $IP:$PORT

# New Terminal
    source myvenv/bin/activate
    cd djangogirls/mysite/

# Django new application
    python manage.py startapp blog

# Add 'blog' as installed app to settings
    INSTALLED_APPS = [
        'blog',


# Django models
https://tutorial.djangogirls.org/en/django_models/

edit models
migrate db
    python manage.py makemigrations 
    python manage.py migrate

# Create admin ubuntu
    python manage.py createsuperuser
    ubuntu
    Kxx@xx16
    
# Django admin
https://tutorial.djangogirls.org/en/django_admin/
    from django.contrib import admin
    from .models import Post
    
    admin.site.register(Post)
#  Visit website's admin# djangogirlsx0930
