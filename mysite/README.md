# Django-Projects using python3

Install Django
$] python3 -m pip install Django

#Creating Project
#$] django-admin startproject mysite
#Create poll App
#$] python3 manage.py startapp polls

Database setup
$] python3 manage.py makemigrations polls
$] python3 manage.py sqlmigrate polls 0001
$] python3 manage.py migrate

To run the code execute the below command
$] python3 manage.py runserver
