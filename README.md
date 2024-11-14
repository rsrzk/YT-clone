# YT-clone

## Video sharing app

This app will allow a user to upload videos to share to the site. There will also be pages available allowing the user to update the uploads as well as delete the video.

## About

This repository is for following Legion Script's Video Sharing App using Django tutorial on Youtube https://www.youtube.com/watch?v=T4XZgW3nEX4&list=PLPSM8rIid1a1odNhUPUQiuP5lWTTp82qy

Stopped tutorial video at Pt 2 : 50.00 need to add in CSS

Alternatively, the written tutorial is on Medium https://legionscript.medium.com/building-a-video-sharing-website-part-1-setup-crud-operations-da2c2699ec9a
_I tried to follow the written tutorial, but it was more effective to follow the YT video_


Resources for the tutorial can be found here https://github.com/legionscript/Video-Sharing/tree/master

How to for venv:

- to create venv: `py -m venv .venv`
- to activate venv: `source .venv/Scripts/activate`
- to deactivate venv: `deactivate`

How to for Django

- to install Django `pip install Django`
- to create new project `django-admin startproject videosharing`
- to run Django `py manage.py runserver`
- to quit the server `CTRL + c`
- to create new app `py manage.py startapp <name>` e.g. new app named videos `py manage.py startapp videos`
- to migrate database `py manage.py migrate`
- for new migration, need to first make migration `py manage.py makemigrations`
- get list of commands `py manage.py`
- to access application shell `py manage.py shell`
- to exit shell `exit()`
- create super user `py manage.py createsuperuser`
- super user credentials (user: admin, pass: admin)
- extra user (user: user2, pass: testerapp2)
