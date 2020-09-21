# RottenPotatoes demo app: getting started

This app is associated with the [ebook](http://www.saasbook.info) Engineering Software as a Service.

To get started:

0. checkout this repository from Github classroom, and make a local clone

0. Then `cd rottenpotatoes-rails-intro` to change to the app's directory.

0. Run the command `bundle install --without production` to make sure all the gems
(libraries) used by the app are in place.

0. Run `bundle exec rake db:setup` to create the initial database.

0. Set local evironmental variables
```
export PORT=26543      # This must be a unique number on your computer
                       #   when using a share computer (i.e. the university lab computers,
                       #   choose a number between 25999-49999 that no-one else is using
export IP=127.0.0.1    # This is the ip for localhost
```  

0. Run `rails server -p $PORT -b $IP` to start the app.  Cloud9 will pop
up a window showing the URL to visit in your browser to interact with
the running app.
