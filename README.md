# ovensensorweb
*This README is __in progress ...__*

Assumes:
- You are using CMD.EXE. Switch path separator if on Mac/Linux.
- You have git, python, django and npm installed.
- You are starting in your home directory (e.g,. C:\Users\\*you*).

Install Steps:
- cd Documents
- mkdir Github
- cd Github
- git clone https://github.com/chrisxkeith/ovensensorweb.git
- cd ovensensorweb\\ovensensorapp\\static\\ovensensorapp
- npm install chart.js --save
- *You should see something like:*

  > chart.js@2.7.2 node_modules\chart.js
  > ├── chartjs-color@2.2.0 (color-convert@0.5.3, chartjs-color-string@0.5.0)
  > └── moment@2.22.2

- cd ..\\..\\..\
- *Set up your virtual environment with mkvirtualenv* (http://virtualenvwrapper.readthedocs.io/en/latest/command_ref.html)
- workon ovensensorproject
- python manage.py runserver
- *You should see something like:*

  > ... to come ...

- *In your browser* : ... to come ...
