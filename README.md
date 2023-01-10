# Description
A blog site project for interaction via the API.

# Technology
Django 3.2
Python 3.7

# Installation
```
git clone 
```

```
cd 
```

Create and activate a virtual environment:

```
python -m venv env
```

```
. env/Scripts/activate
```

Install dependencies from a file requirements.txt:

```
python -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

```
cd 
```

Perform migrations:

```
python manage.py migrate
```

Launch a project:

```
python manage.py runserver
```


# Examples
GET [list of commands with examples](http://127.0.0.1:8000/redoc/#tag/api),

GET [list of posts](http://127.0.0.1:8000/api/v1/posts/),

POST [make of post](http://127.0.0.1:8000/api/v1/posts/), need authorization.

# Author
It's me, Dmitry Kolomeytcev
