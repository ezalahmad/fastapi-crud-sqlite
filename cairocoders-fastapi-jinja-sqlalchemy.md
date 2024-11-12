# Cairocoders FastAPI Jinja SQLAlchemy

Table of Content

1. [Introduction](#introduction)
    * [Create virtual environment](#create-virtual-environment)
    * [Install FastAPI](#install-fastapi)
    * [Install SQLAlchemy](#install-sqlalchemy)


# Introduction
<a name="introduction"></a>

We are going to create a CRUD web application using FastAPI, Jinja and SQLAlchemy.

Browse the source code [here](https://github.com/cairocoders/cairocoders-fastapi-jinja-sqlalchemy)

Go to FastAPI official page [here](https://fastapi.tiangolo.com/)

Now we are going to create a virtual environment and install the required packages:

# Create virtual environment
<a name="create-virtual-environment"></a>

```
python3 -m venv venv
source venv/bin/activate
pip install "fastapi[standard]"
```
Run `pip list` to see the installed packages.



```bash
Python 3.11.2 (main, Aug 26 2024, 07:20:54) [GCC 12.2.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> from fastapi import FastAPI
>>> from fastapi.templating import Jinja2Templates
```

Launch the application using `uvicorn main:app --reload` or `fastapi dev main.py`

