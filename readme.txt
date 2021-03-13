1. pip install virtualenv

2. virtualenv env

3. Set-ExecutionPolicy unrestricted -- power shell

4. env\Scripts\activate.ps1  

5. pip install flask


6. python

>>> from app import db
>>> db.create_all()

--- Deploy project on heroku

1. pip install gunicorn
2. pip freeze > requirements.txt
3. create Procfile
inside Procfile type...
web : gunicorn app:app

4. Inside terminal
5. heroku
6. heroku login
Enter your credentials
7. git init
8. git add .
9. git commit -m 
10. heroku create "name"
11. git push heroku master

https://todo-faisal.herokuapp.com/
