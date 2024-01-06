
## Setting up a virtual environment: 

- windows (python 3.10):
```
py -3.10 -m pip install virtualenv
```
```
py -3.10 -m venv env
```
```
env\Scripts\activate
```

- linux & mac:
```
pip3 install virtualenv
```
```
virtualenv env
```
```
source env/bin/activate
```

## Installing the packages
windows:
```
pip install flask flask-sqlalchemy
```
linux & mac:
```
pip3 install flask flask-sqlalchemy
```

## To run the project

<!-- to create the database:
```
python
```
```
>>> from app import app, db
```
```
>>> db.create_all()
```

To run the project:
```
python app.py
``` -->