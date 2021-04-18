# Todo_server

To-do list application used to add task, list all tasks, chek completed tasks, update and delete task.
Django Rest Framework used to built API service.
Django-cors-header used for handling the server headers required for CORS. Used serializer to represent data in JSON format.
Deployed at Heroku. 
## Technologies

Project is created with:
Python,
Django,
Django REST framework,
SQLite3


### Setup
To run this project install it localy using pip:

```
$ cd ./Todo_server
 pip install -r requirements.txt
```

Migrate:
```
python manage.py migrate
```
To Start Server:

```
python manage.py runserver
