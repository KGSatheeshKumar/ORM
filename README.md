# Ex02 Django ORM Web Application
## Date: 

## AIM
To develop a Django application to store and retrieve data from a Book database using Object Relational Mapping(ORM).

## Entity Relationship Diagram

Include your ER diagram here

## DESIGN STEPS

### STEP 1:
Clone the problem from GitHub

### STEP 2:
Create a new app in Django project

### STEP 3:
Enter the code for admin.py and models.py

### STEP 4:
Execute Django admin and create details for 10 books

## PROGRAM

```
1) To create Django Project :
  In commandPrompt:
    a) django-admin startproject project1
    b) cd project1
    c) code .

2) To create Application :
    a) Open new terminal
    b) python manage.py startapp app1
3) Models.py :

# Create tables :

from django.db import models

class Student(models.Model):
    stu_id=models.IntegerField()
    stu_name=models.CharField(max_length=30)
    dept=models.CharField(max_length=20)
    email=models.CharField(max_length=30)
    mobile_no=models.IntegerField()

4)Admin.py :

from django.contrib import admin
from app1.models import Student

admin.site.register(Student)

5) Ternimal :

    a) python manage.py makemigration
    b) python manage.py migrate
    c) python manage.py createsuperuser
          - Add UserName and Password for Django server

6) Login to Django administration :
          - Add Student data and Save it


```

## OUTPUT




## RESULT
Thus the program for creating a database using ORM hass been executed successfully
