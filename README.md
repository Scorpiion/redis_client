# Redis client on Sourcevoid

## Note

This is combination of the "redis_server" and "app_terminal" repos to make it easier to debug and test redis. This app will install redis so that the redis-cli command exists, and then it will run a copy of the app_terminal so you can access from the browser. 

## Download and build zip (or clone/fork the repo to your Github)
    git clone git@github.com:Scorpiion/redis_client.git
    cd redis_client
    ./zip.bash
    
## Deploy env

Follow normal procedure @ https://cloud.sourcevoid.com. 

# Security Notice!

Currently this should be considered a prof of concept, at this point in time anyone with the right url can access this terminal when you have started it. A simple security meassure could be to simply change the url to include a long random string, as long as no one else know the url they can't access the terminal.

Relying on a random url is not a good setup though, it would be much better to setup something like basic auth instead. It should be fairly simply to add to this app, I have just not gotten it to work yet. Pull requests are welcomed!

