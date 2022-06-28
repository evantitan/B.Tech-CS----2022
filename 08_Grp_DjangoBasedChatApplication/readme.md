### text chat and Video calling with WebRtc and Django

## Create Virtual Environment with pip3

```
virtualenv virtual/webrtc -p python3 

```

## Install Django and all modules

```

pip3 install django
django-admin startproject webrtc
django-admin startproject webrtc .
pip3 install Pillow
pip3 install django-extensions
pip3 install djangorestframework
pip3 install django-rest-auth
pip3 install django-cors-headers
pip3 install django-filter
pip3 install django-froala-editor
pip3 install django-ckeditor
pip3 install fcm_django
pip3 install mysqlclient
LDFLAGS=-L/usr/local/opt/openssl/lib pip install mysqlclient

```

## Update requirement.txt file

```
pip3 freeze > requirements.txt

```

### Create New App using ---

``` 
python manage.py startapp mychat 

```
## Run Django

```
python manage.py runserver
python manage.py runserver 8080
python manage.py runserver 0:8000
python manage.py runserver 192.168.1.4:8000

```

## Create Superuser

``` 
python manage.py changepassword username

```

## Make Migrations of single app or Project

```
python manage.py makemigrations
python manage.py makemigrations blog

```
## Run on local System

```
DJANGO_SETTINGS_MODULE=webrtc.settings.local python manage.py runserver

```

## Run on production server

```
python manage.py runserver

```

## Static files on production server

```
python manage.py collectstatic
python manage.py collectstatic --noinput
python manage.py collectstatic --noinput --clear

```













