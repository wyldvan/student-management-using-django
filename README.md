# Pre-Requisites:
1. Install Git Version Control :octocat:
[ https://git-scm.com/ ]

2. Install Python Latest Version :snake:
[ https://www.python.org/downloads/ ]

3. Install Pip (Package Manager) :package:
[ https://pip.pypa.io/en/stable/installing/ ]

> [!NOTE]
> Alternative to Pip is Homebrew

## Installation
**1. Create a Folder where you want to save the project**
___
**2. Create a Virtual Environment and Activate**

Install Virtual Environment First
```
$  pip install virtualenv
```
___
Create Virtual Environment

*For Windows*
```
$  python -m venv venv
```
*For Mac*
```
$  python3 -m venv venv
```
*For Linux*
```
$  virtualenv .
```
___
Activate Virtual Environment

*For Windows*
```
$  source venv/scripts/activate
```

*For Mac*
```
$  source venv/bin/activate
```

*For Linux*
```
$  source bin/activate
```
___
**3. Clone this project**
```
$  git clone https://github.com/jobic10/student-management-using-django.git
```
___
*Then, Enter the project*
```
$  cd student-management-using-django
```
___
**4. Install Requirements from 'requirements.txt'**
``` python
$  pip3 install -r requirements.txt
```
___
**5. Add the hosts**

- Got to settings.py file 
- Then, On allowed hosts, Use **[]** as your host. 
```python
ALLOWED_HOSTS = []
```

> [!WARNING]
> Do not use the fault allowed settings in this repo. It has security risk!
___
**6. Now Run Server**

Command for PC:
```python
$ python manage.py runserver
```
___
**7. Login Credentials**

Create Super User (HOD)
Command for PC:
```
$  python manage.py createsuperuser
```

Command for Mac:
```
$  python3 manage.py createsuperuser
```

Command for Linux:
```
$  python3 manage.py createsuperuser
```


:information_source:Then Add Email and Password

**or Use Default Credentials**

*For HOD /SuperAdmin*
Email: admin@admin.com
Password: admin

*For Staff*
Email: staff@staff.com
Password: staff

*For Student*
Email: student@student.com
Password: student

:snake::octocat::package:
