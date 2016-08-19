# blocitoff test
self-destructing to-do lists

Made with my mentor at [Bloc](http://bloc.io).


**commands **

To load rails server: :
# rails s -p $PORT -b $IP

To remove files that you don't need:
git clean -f -d

To reset database:

rake db:reset drops the database and uses the seed file to repopulate it.

then migrate database

rake db:migrate

#skips a pending commit and forces the current commit:
git push --force

HEROKU database commands:
You can use heroku pg:reset DATABASE command to reset the entire database. The command will simply drop and create the database.

You have to use heroku rake db:migrate to create the tables then.

Alternatively you can use rake db:reset command locally and then run heroku db:push to update the production db.

git branch -a / shows all local and remote branches
git granch -r / shows only remote branches.