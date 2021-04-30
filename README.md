# Restful-API-for-book-management-system-using-flask-with-SQLAlchemy

**This repo consists of a book management system in which you can perform all the CRUD operations like insert, update, delete and retrieve. This application is actually a restful API built using flask with SQLALchemy and Marshmallow as ORM (Object-Relational-Mapper).**

## How to run

- Download the zip file and extract
- Open any IDE
- Firstly, execute this command

  $ pip install pipenv

- Then, enter the pipenv shell by entering the command
  
  $ pipenv shell

- Then install all the required modules by entering this command

  $ pipenv install flask flask_sqlalchemy flask_marshmallow marshmallow-sqlalchemy
  
- Then, enter to python shell to intialize the database

  $ python

  `>>>` from main import db
  
  `>>>` db.create_all()
  
  `>>>` exit()

- Now that the db is created, run the main.py by entering the command

  $ python main.py

- a localhost server is created with port 5000
  
  http://localhost:5000/ 

- Now, you can happily execute your CRUD operations through POSTMAN.
  

