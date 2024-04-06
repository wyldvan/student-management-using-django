# Pre-Requisites:
1. Install Git Version Control
[ https://git-scm.com/ ]

2. Install Python Latest Version
[ https://www.python.org/downloads/ ]

3. Install Pip (Package Manager)
[ https://pip.pypa.io/en/stable/installing/ ]

> [!NOTE]
> Alternative to Pip is Homebrew

## Installation
**1. Create a Folder where you want to save the project**
___
**2. Create a Virtual Environment and Activate**

> Install Virtual Environment First
```
$  pip install virtualenv
```
___
>Create Virtual Environment

For Windows
```
$  python -m venv venv
```
For Mac
```
$  python3 -m venv venv
```
For Linux
```
$  virtualenv .
```
___
> Activate Virtual Environment

For Windows
```
$  source venv/scripts/activate
```

For Mac
```
$  source venv/bin/activate
```

For Linux
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


