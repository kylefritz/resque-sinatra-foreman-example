#Quick demo of sinatra app plus resque plus foreman

    $ bundle install
    $ foreman start

checkout http://localhost:9393/ for the app that queues items. Thanks to [redistogo](http://blog.redistogo.com/2010/10/04/resque-with-sinatra/) for most of the code

checkout http://localhost:5678 for the resque monitoring app


# with rack

or start resque

   $ rake resque:work

and in another start both web apps (one server)

   $ rackup
