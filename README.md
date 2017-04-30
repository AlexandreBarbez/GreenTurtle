#BigGreenTurtle project

##Setup
Acces to local Database :

> brew services start postgres

Connect to DB : turtle
With login/password : alex/lolilol

Set local database var with :

> export DATABASE_URL=postgres://alex:lolilol@localhost:5432/turtle
 
Set local Port var with :

>export PORT=8080

Run the app locally with heroku local
