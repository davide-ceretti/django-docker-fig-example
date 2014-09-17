django-docker-fig-example
=========================

A simple Django web application running on Docker + fig.

The ultimate aim is to create something portable, that can be developed on, easy deployable with continous delivery.

Install
-------

First, you need docker installed. See http://docs.docker.com/installation/ubuntulinux/
Second, you need fig installed. See http://www.fig.sh/install.html.

Run application
---------------

fig up

Run management commands
-----------------------

fig run web python manage.py migrate
