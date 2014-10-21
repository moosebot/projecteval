Installation
===========

1) Download Project from Git
2) Go to terminal
3) Change to project home directory (with run.py file)
4) Use virtual environment ("source env/bin/activate")
  - If the virtual environment doesn't work
    - Delete the env folder
    - Create a new virtual environment ("virtualenv env")
5) Install the following software: (commands in Linux)

  - Flask
  pip install flask

  - Flask-Login
  pip install flask-login

  - Flask-WTF
  pip install flask-wtf

  - SQLAlchemy
  pip install flask-sqlalchemy

  - Postgresql
  sudo apt-get install postgresql

  - Psycopg2
  pip install psycopg2

6) Run the project ("python run.py")
7) Open up pgAdmin III and run the game-testdata.sql insert script.
8) Test the app 
  - Go to 0.0.0.0:8080/login for a html template 
  - Go to 0.0.0.0:8080/games for a sample api response
9) If anything is missing (in regards to installation), add 
   it to this file.
