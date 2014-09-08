foodbot-webapp
===========
(Deprecated, see: https://github.com/robgraeber/foodbot-webapp/)

Rest API + client-side app server.

Dependencies: node, bower, npm, gulp, nodemon  
(Also needs foodbot-scraper to populate the database)

To run: fill out run.sh with your API keys, and type '. run.sh'

run.sh:
```
#!/bin/bash
gulp build

export GOOGLEAPIKEY='@@@@@@'
export MONGOURL='mongodb://@@@@@@@:27017/@@@@@'
export PORT=8000
nodemon server.js
```
During development: type 'gulp' to compile and watch files

Please fork and improve! :)



