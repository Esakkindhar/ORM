# Ex02 Django ORM Web Application
# Date:23-03-2025
# AIM
To develop a Django application to store and retrieve data from Movies Database using Object Relational Mapping(ORM).

## DESIGN STEPS
## STEP 1:
Clone the problem from GitHub

## STEP 2:
Create a new app in Django project

## STEP 3:
Enter the code for admin.py and models.py

## STEP 4:
Execute Django admin and create details for 10 books

# PROGRAM
```
admin.py
from django.contrib import admin
from .models import movie, movieAdmin
admin.site.register(movie, movieAdmin)

models.py
from django.db import models
from django.contrib import admin

class movie(models.Model):
    mid = models.CharField(max_length=20, help_text="Employee ID")
    name = models.CharField(max_length=100)
    cost = models.IntegerField(max_length=100)
    mtype = models.CharField(max_length=100)
    mlength = models.FloatField()

class movieAdmin(admin.ModelAdmin):
    list_display = ('mid', 'name', 'cost', 'mtype', 'mlength')

```

# OUTPUT

![WhatsApp Image 2025-03-25 at 10 09 02_d7271987](https://github.com/user-attachments/assets/5030edc2-d6e8-4d74-8a44-a94c602ec993)


## Name:Esakkindhar A
## Reg:212224040085

# RESULT
Thus the program for creating a database using ORM hass been executed successfully

Include the screenshot of your admin page.


## RESULT
Thus the program for creating movies database using ORM hass been executed successfully
