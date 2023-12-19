# Django ORM Web Application

## AIM
To develop a Django application to store and retrieve data from a database using Object Relational Mapping(ORM).

## Entity Relationship Diagram

![ER relation](https://github.com/Narendran-sec/django-orm-app/assets/147473131/dd626c4f-dbbe-4432-866a-0663b7054802)

## DESIGN STEPS

### STEP 1:
Create the problem from GitHub

### STEP 2:
Create a new app in Django project

### STEP 3:

Enter the code for admin.py and models.py

## PROGRAM

```python
models.py
from django.db inport models
from django.contrib import admin
class Football_player (models.Model):
     Name-models.CharField(max_length=20)
     Dob models.DateField()
     Height models. IntegerField()
     Address-models.CharField(max_length=100)
     MobileNo=models. IntegerField()
class Football_player (admib.ModelAdmin):
     list_display=["Name", "Bob", "Height", "Address","MobileNo"]
```


```python
admin.py
from django.contrib impot admin
from.models import Football_player,Football_playerAdmin
admin.site.register(football_player, Football_playerAdmin)
```
## OUTPUT

![output](https://github.com/Narendran-sec/django-orm-app/assets/147473131/c920007e-5fb3-4246-b4c0-9a4f47fb126c)



## RESULT
Thus the program for creating a database using ORM has been executed successfully
