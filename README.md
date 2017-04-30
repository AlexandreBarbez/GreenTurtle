#BigGreenTurtle project

##Setup
Acces to local Database :

> $ brew services start postgres

Connect to DB : turtle
With login/password : alex/lolilol

Set local database var with :

> $ export DATABASE_URL=postgres://alex:lolilol@localhost:5432/turtle
 
Set local Port var with :

> $ export PORT=8080

Run the app locally with heroku local

App is availlable locally at "localhost:$PORT"

:D

To put it on heroku : add it to git with 
> $ git add .

then commit with
> $ git commit -m" MESSAGE"

then push on Heroku with 
> $ git push heroku master


To check if a dyno is running the app :

> $ heroku ps

To put one at work on web :

> $ heroku ps:scale web=1

To get the logs :

> $ heroku logs -n NUMLIGNE

