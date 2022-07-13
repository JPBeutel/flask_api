# flask_api
REST API with Flask, SQL Alchemy, and Marshmallow

#Activate venv
> mkdir myproject
> cd myproject
> py -3 -m venv venv
> venv\Scripts\activate

#install dependencies
$ pip install 

#create database
$ python
>> from app import db
>> db.create_all()
>> exit()

#run server (http://localhost:5000)
python app.py

# Endpoints
GET/product
GET/product/:id
POST/product
PUT/product/:id
DELETE/product/:id
