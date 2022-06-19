# AIoT Github

## Lecture 15: IoT Flask Web (deploy to heroku)

### step 1 : 複製老師github的內容至自己的github上
![first picture.](/static/step1.png)
### step 2 : install some package


```python
pip insall gunicorn   
Flask==2.0.1 
Jinja2==3.0.1 
psycopg2 
sklearn 
pandas  
numpy 
```
![second picture.](/static/step2.png)

### step 3: add an heroku postgredb

* register heroku account
* go to dashboard
* new an app
![](/static/step3_1.png)
* go to resource and add-on an Heroku postgredb
![](/static/step.png)

### step 4: login to heroku pstgredb using HeidiSQL


```sql
myserver ="<fill-in-Heroku-Postgredb-DB-sever>"
myuser="<fill-in-Heroku-Postgredb-DB-user>"
mypassword="<fill-in-Heroku-Postgredb-DB-pwd>"
mydb="<fill-in-Heroku-Postgredb-DB-db>"

```
![](/static/step4_1.png)
![](/static/step4_2.png)
![](/static/step4_3.png)
### step 5: import postgredb (in db/postgre.db)

![](/static/step5.png)
### step 6: setting db in app.py

![](/static/step6.png)
```sql
myserver ="<fill-in-Heroku-Postgredb-DB-sever>"
myuser="<fill-in-Heroku-Postgredb-DB-user>"
mypassword="<fill-in-Heroku-Postgredb-DB-pwd>"
mydb="<fill-in-Heroku-Postgredb-DB-db>"

```
### step 7: testing locally by running python app.py
![](/static/step7.png)
### step 8: deploy to github (new private github repositoy)

delete .git and git remote add origin master github.com/xxxxx


### step 9: Heroku deploy from github

### step 10: Complete

Sample link 1:
https://awinlab-aiot.herokuapp.com/

Sample link 2: 
https://aiot0529.herokuapp.com/





