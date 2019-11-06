The backend is written in Python 3 and uses "Django" framework. Sqlite3 is used as the default database to store user authentication information.

# Migrate
Any changes made to the python file or database is realized only after performing migration.
### Command: python3 manage.py migrate

# Start the server:
### python3 manage.py runserver 
The server runs at port number 8000.

# Login url:
### 127.0.0.1:8000/account/login
An existing username and password is:
### username: user1
### password: battleship

# admin site url:
There exist an admin site for super users. Its purpose is user creation and deletion in a user friendly way.  
### 127.0.0.1:8000/admin
An existing username and password is:
### username: assignment2
### password: battleship
