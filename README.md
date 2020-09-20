# TODO-LIST

todo list is the program where you can add, delete , reveiw your daily routine task
to setup this follow the following command.
open cmd on your window

!-- first create Virtual environment in your machine --! 
  >virtualenv renv 
# renv is the name of virtual Environment which created in my machine

!-- Activate the Virtual Environment in your machine --!
 >renv\scripts\activate   #this will activate virtual Envirnoment in your machine
 
!-- move to the Virtual Envirnomant Directory--!
>cd renv

!-- Install Djnago --!
>pip install django

!-- Install Django Rest Framework --!
>pip install djangorestframework

!-- now create the Django project insite the activated virtual Environment --!
>django-admin starporject rest
# rest is the name of the django project
>cd rest
>django-admin startapp restapp
>python manage.py runserver
now enjoy server start running 
