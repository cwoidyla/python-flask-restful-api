# python-flask-restful-api
A simple JWT-authenticated RESTful API for managing a book collection.
How to create a Database
This assumes you have a DB constructor called BookModel.py

1. Open Python
2. Issue the following commands:
from BookModel import *
db.create_all()
exit()


Next steps
Flask-RESTful: extension to organize large projects
- can group different routes into single class that matches a resource a client
  is requesting
- Fits well with ORM libraries such as SQLAlchemy

Flask JWT Extended
- Used if you have unique JWT use cases such as:
  - allowing API access for anonymous users,
  - those who are authenticated,
  - can use other encrypting algorithms for JWT tokens
