# ovensensorweb
*This README is __in progress ...__*

Assumes:
- You are using CMD.EXE. Switch path separator if on Mac/Linux.
- You have python, django and npm installed.
- You are starting in your home directory (e.g,. C:\Users\\*you*).

Install Steps:
- cd Documents
- mkdir Github
- git clone *this repository*
- cd ovensensorweb\ovensensorapp\static\ovensensorapp
- npm install chart.js --save
- cd ..\\..\\..\
- *Set up your virtual environment with mkvirtualenv* (http://virtualenvwrapper.readthedocs.io/en/latest/command_ref.html)
- workon ovensensorproject
- python manage.py runserver
- *In your browser* : C:/Users/*you*/Documents/Github/ovensensorweb/ovensensorapp/static/ovensensorapp/index.html
