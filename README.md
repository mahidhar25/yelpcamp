YelpCamp

YelpCamp is a project that was completed as a part of Colt Steele's bootcamp. My version of YelpCamp has a few tweaks beyond what was coded in class.

Setup 

Different setups are needed if you plan on using YelpCamp locally (or Cloud9) verus the Heroku + MongoLab setup. This is accomplished using enviornment variables.

Local/Cloud9 Setup

Run the following commands in the terminal. Be sure to update information as necessary.

export DATABASEURL=mongodb://localhost/yelp_camp

Heroku + MongoLab setup

Update the variables as follows:

DATABASEURL "mongodb://<dbuser>:<dbpassword>@ds127982.mlab.com:27982/mahidharreddy"


This can be accomplished on the Heroku site by accessing the Config Vars on the Settings page.
Alternatively this can be done on the command line with the following commands:

heroku config:set DATABASEURL='mongodb://\<dbuser>:\<dbpassword>@1234.mlab.<span></span>com:19990/yelp-camp'
heroku config:set SESSION_SECRET='Whatever phrase you choose'
Deployed

The app is deployed here at Heroku (also using MongoLab).

https://glacial-peak-79446.herokuapp.com/
