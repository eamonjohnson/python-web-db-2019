# python-web-db-2019
This is a basic web application.  

Demonstration goals:
* Python project setup.
* Connecting to MySQL with SQLAlchemy.
* Serving web pages with Flask.
* Accepting input from the web and modifying the database.

# setup steps
For this project we will use virtualenv and pip to manage packages.

We start at the bash shell by cloning the project, switching to the project directory, creating a virtual environment with the python3 interpreter, and then installing required packages into the virtual environment.

```
$ git clone git@github.com:eamonjohnson/python-web-db-2019.git
$ cd python-web-db-2019.git
$ virtualenv -p `which python3` venv
$ source venv/bin/activate
(venv) $ pip install -r requirements.txt
```

Now that the virtual environment is activated and packages are installed, we can run the application.  The config file provided with the project will run on the CWRU EECS 341 class server.

```
(venv) $ python run.py
```
