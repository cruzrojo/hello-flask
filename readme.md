# Flask App

The following project was buit during my course with Battega. It has full CRUD functionaity.

please see:
https://github.com/bottega-code-school/hello-flask/tree/0f210cc30c2a46bd4ed3a2cd2f8ff43b6e42a7a6
http://flask-sqlalchemy.pocoo.org/2.3/
http://flask-marshmallow.readthedocs.io/en/latest/
https://marshmallow-sqlalchemy.readthedocs.io/en/latest/

### Create Database

Added the SQLlight and created the database. The database has 1 table with the first column being the primary key, the second column being 'title' and the third column being called 'content'.

- If you need to create a database.  Hop into a python repl and run the following commands.
- When you're done you should have an app.sqlite file.  That file will be your database.
```
>>> from app import db
>>> db.create_all()
```
