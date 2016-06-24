Ruby version is specified at the end of the `Gemfile`. `.rvmrc` is a file that __RVM__ looks for to automatically know which ruby version to set and which gemset to use (a gemset is like a container/environment space). 


Specified database is Postgresql, which is the open source version of MySQL. Heroku likes Postgres. You'll need to have that installed. I used Homebrew for that. `/db/databse.yml` is where those configgers are for the different environments. 



To get er up and running - 
- `$ rails db:setup `
- `$ rails db:migrate`
- `$ rails s` 


