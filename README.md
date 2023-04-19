# Web-Techies
Team-Members:Tridip Kundu, Tanmoy Chowdhury , Swaranava Pramanik

Topics:A mobile app that provides free access to educational resources, such as digital textbooks, interactive tutorials, and practice exercises, for underprivileged students in remote or underserved areas. The app could be designed to work offline and cater to different learning levels and subjects, empowering students to continue learning despite limited access to formal education.

# Django python Boilerplate

[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.0-4baaaa.svg)](code_of_conduct.md)
[![License: MIT](https://img.shields.io/github/license/vintasoftware/django-react-boilerplate.svg)](LICENSE.txt)


### Main features

* Separated dev and production settings

* Example app with custom user model

* Bootstrap static files included

* User registration and logging and Adnim registration and logging in as demo

* Procfile for easy deployments

* Separated requirements files

* SQLite by default if no env variable is set

# Usage

To use this template to start your own project:

### Existing virtualenv

If your project is already in an existing python3 virtualenv first install django by running

    $ pip install django
    
And then run the `django-admin.py` command to start the new project:

    $ django-admin.py startproject \
      --template=https://github.com/TRIDIP220/Web-Techies \
      --extension=py,md \
      <project_name>
      
### No virtualenv

This assumes that `python3` is linked to valid installation of python 3 and that `pip` is installed and `pip3`is valid
for installing python 3 packages.

Installing inside virtualenv is recommended, however you can start your project without virtualenv too.

If you don't have django installed for python 3 then run:

    $ pip3 install django
    
And then:

    $ python3 -m django startproject \
      --template=https://github.com/TRIDIP220/Web-Techiesr \
      --extension=py,md \
      <project_name>
      
      
After that just install the local dependencies, run migrations, and start the server.

{% endif %}

# {{ project_name|title }}

# Getting Started

First clone the repository from Github and switch to the new directory:

    $ git clone git@github.com/USERNAME/{{ project_name }}.git
    $ cd {{ project_name }}
    
    ### Backend
- `django` for building backend logic using Python
- `djangorestframework` for building a REST API on top of Django
- `django-webpack-loader` for rendering the bundled frontend assets
- `django-js-reverse` for easy handling of Django URLs on JS
- `psycopg2` for using PostgreSQL database
- `sentry-sdk` for error monitoring
- `python-decouple` for reading environment variables on settings files
- `celery` for background worker tasks
- `django-debreach` for additional protection against BREACH attack
- `whitenoise` and `brotlipy` for serving static assets

#### Run the backend app
- With the virtualenv enabled, go to the `backend` directory
- Create the migrations for `users` app: 
  `python manage.py makemigrations`
- Run the migrations:
  `python manage.py migrate`
- Run the project:
  `python manage.py runserver`
- Open a browser and go to `http://localhost:8000` to see the project running . 

Activate the virtualenv for your project.
    
Install project dependencies:

    $ pip install -r requirements/local.txt
    
    
Then simply apply the migrations:

    $ python manage.py migrate
    

You can now run the development server:

    $ python manage.py runserver


# Full vedio description in our project 

https://user-images.githubusercontent.com/105142693/232986773-4e9699ff-3719-41fe-ac05-7de1921ce28f.mp4


# Home page our final Project 
![Home Image](https://user-images.githubusercontent.com/105142693/232225070-e5180353-b461-4e88-8fe1-ccce6de18d82.jpg)

# Mobile Application demonstration by our team :

![WhatsApp Image 2023-04-15 at 19 06 10](https://user-images.githubusercontent.com/112960982/232227598-cc2f65f6-db24-4140-b2b2-4d3404170a9f.jpg)



