# Python Feedback Application 
A python feedback application to provide online feedback for a dealership. 

### Dependencies
* **mailtrap** for email features. 
* **PostgreSQL** for database features. 
* **flask** python web framework. 
* **flask-sqlalchemy** python web framework for sql database. 
* **gunicorn** http server needed for deploying the app on heroku. 

### Notes 
To run the app clone it create the pipenv and run 
```python 
# to run the env 
pipenv shell
# to run the app 
python app.py
```

* Personal notes
> database was created with python: 
```python
from app import db 
db.create_all()
exit()
```
* To create the requriements fle 
```python
pip freeze > requirements.txt
```