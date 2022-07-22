# DJANGO

## Crear entorno virtual

<p><em>$ virtualenv django_env</em></p>
<p><em>$ source django_env/bin/activate</em></p>

## Levantar Django

<p><em>$python django_env/bin/django-admin startproject test_project</em></p>

## Git

<p><em>git push git@github.com:german001101/django.git main<em></p>
<p><em>git pull git@github.com:german001101/django.git main<em></p>

## Django

pip install Django==4.0.6

### Verificar que se tiene instalado

<p>$ pip freeze</p>

* asgiref==3.5.2
* backports.zoneinfo==0.2.1
* Django==4.0.6
* sqlparse==0.4.2
  
### Levantar Django

> python manage.py runserver

### Migration(Base de datos y el proyecto)

> python manage.py migrate

### Crear superUsuario

* python src/manage.py createsuperuser
* Username (leave blank to use 'gburgos'): 
* Email address: german001101@gmail.ocm
* Password: 
* Password (again): 
* Superuser created successfully.

### Levantar una app con django

* python manage.py startapp boletin

### Registro de la app

* Ir a settings.py > INSTALLED_APPS

![image](image/settings_Install.png)

### Escribir Modelos

boletin > models.py\

![image](image/models_1.png)
### Migrar

* python manage.py makemigrations
* python manage.py migrate

![image](image/makemigrations.png)

