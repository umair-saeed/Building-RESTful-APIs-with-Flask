I have build this demo to make some notes for myself on RESTful APIs with Python 3 and Flask. These super simple API example are to remind myself whenever I need to revisit Flask. For this reason I've kept everything in a single Python file as this is not a full project.

I have used SQL Lite DB to store the User and Planets information. DB creation and seeding is part of the code.
 
 

## What did I use in this demo?
### Tools
* I used Postman as a front-end.
* SQLite Browser to open the database file.
### Framework and other details
* Flask
* jsonify used to return JSON instead of text, along with status codes.
* URL parameters, URL variables & conversion filters
* SQLAlchemy as object-relational mapper (ORM)
* Serializing SQLAlchemy results with Marshmallow
* JSON Web Tokens to authenticate API users
* API functions
  * Retrieving a single planet's details, GET
  * Adding new planets with a POST method
  * Updating a planet using a PUT method
  * Deleting a planet with DEL
