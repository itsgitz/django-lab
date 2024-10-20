> Notes: I used Linux on this lab, so if you are using Windows some of the steps in
this lab will be failed.

# Prerequisites
1. Create python virtual environment for better development process.

```sh
$ python3 -m venv venv
```

2. Activate the python virtual environment.

```sh
$ source venv/bin/activate
```

# Installation

Installing **Django** web framework.

```sh
$ python3 -m pip install Django
$ python3 -m django --version
```

# Creating a project

```sh
$ mkdir django-lab
$ django-admin startproject getting_started django-lab
$ cd django-lab
$ python3 manage.py runserver
```

# Tutorial Sources
I followed the tutorials from the **Django** official documentation website for the fundamentals.
And the documentation from **Flowbite** for the **Tailwindcss** installation.

* [Django - Chapter 1](https://docs.djangoproject.com/en/5.1/intro/tutorial01/)
* [Django - Chapter 2](https://docs.djangoproject.com/en/5.1/intro/tutorial02/)
* [Django - Chapter 3](https://docs.djangoproject.com/en/5.1/intro/tutorial03/)
* [Django - Chapter 4](https://docs.djangoproject.com/en/5.1/intro/tutorial04/)
* [Django - Chapter 5](https://docs.djangoproject.com/en/5.1/intro/tutorial05/)
* [Django - Chapter 6](https://docs.djangoproject.com/en/5.1/intro/tutorial06/)
* [Django - Chapter 7](https://docs.djangoproject.com/en/5.1/intro/tutorial07/)
* [Tailwind CSS Installation Inside the Django project](https://docs.djangoproject.com/en/5.1/intro/tutorial08/)