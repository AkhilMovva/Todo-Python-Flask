# Todo-Python-Flask
Simple Todo list Using Python Flask

- https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/

 ```sh
$python
- from app import db
- db.create_all()
- exit()
```
Host the app on HEROKU
https://www.heroku.com/
https://devcenter.heroku.com/articles/heroku-cli

 ```sh
touch Procfile
web: gunicorn app:app
heroku login

 git init
 git add .
 git commit -m "Init app"
 heroku create flaskpythonTodo
 git remote -v
 git push remote -v
 ```
![Screenshot 2021-10-14 035638](https://user-images.githubusercontent.com/23433121/137404347-de2da85a-8517-422e-a6fd-f5bb5e2755d9.png)
![Screenshot 2021-10-14 035708](https://user-images.githubusercontent.com/23433121/137404354-0ea9e416-7523-4071-856a-21a1227299dc.png)
