# 🚀 Django Project Setup Guide

### **Check Python Version**
Before you begin, make sure you have Python installed. You can check the version by running:
```bash
python --version
````
If do you not have a python installed, use ```winget install Python.Python.3.13``` or latest version. 
Or install in <a href="https://www.python.org/downloads/">Python Oficial Site.

### :computer: **Create a Virtual Environment**
It's a good practice to use a virtual environment to manage your project dependencies. To create one, run:
```bash
python -m venv name_venv
````
then in the directory you can use ```.\name_venv\Scripts\activate``` or ```cd name_venv``` and ```.\Scripts\activate```
### :floppy_disk: **Install Django**
In your venv, use
```pip install django``` -> To install django,

```python -m django startproject projectName``` -> Create django project

```cd projectName``` -> To navigate a django projects directory, 

So uses ```python manage.py createsuperuser``` to create adm credentials. 
 
###  🎉**Run the Development Server**
````bash
python manage.py runserver
````
### :bomb: **Create apps**
````bash
python manage.py startapp app_name
````
### :fire: **Create Urls**
In your app created, nav for ```views.py```
````bash

from django.shortcuts import render
from django.http import HttpResponse

def home(request):
    return render("Hello World")

````
then, got to ```urls.py``` in directory

`````bash
from django.contrib import admin
from django.urls import path
from app import views

urlpatterns = [
    path('admin/', admin.site.urls),
    path('home/', views.home),
]
``````

<h1>Extra</h1>

How to activate executions Scripts in Windows for activate venv. 

```
>>>Set-ExecutionPolicy
````
```
>>>RemoteSigned
```
or 
```
>>>Get-ExecutionPolicy <select_preference>
```

<p>Preferences</p>

```Restricted:```Does not allow loading or running PowerShell configuration files or scripts.

```AllSigned:``` Only allows scripts signed by a trusted publisher, even if they were written locally.

```RemoteSigned:``` Allows local scripts to run, but requires scripts downloaded from the internet to be signed.

```Unrestricted:``` Runs all scripts, with a possible prompt for unsigned scripts.

```Bypass:``` No restrictions on script execution.

```Undefined:``` Removes the current execution policy unless set by a group policy.

💻✨
