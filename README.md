# Omdena_MLOps-assignment3

# Deploying Flask App on Heroku

```
python3 -m venv venv
source venv/bin/activate
pip install gunicorn 
```



Heroku manages app deployments with Git, the popular version control system.

Before you can deploy your app to Heroku, you need to initialize a local Git repository and commit your application code to it.

```
heroku login
git add .
git commit -am "make it better" 
heroku git:remote -a flask-heru
git push heroku master
``` 

```
Enumerating objects: 1614, done.
Counting objects: 100% (1614/1614), done.
Delta compression using up to 4 threads
Compressing objects: 100% (1589/1589), done.
Writing objects: 100% (1614/1614), 5.11 MiB | 350.00 KiB/s, done.
Total 1614 (delta 121), reused 0 (delta 0), pack-reused 0
```

