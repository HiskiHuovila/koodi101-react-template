# Overview

TODO joku lyhyt selitys tähän

# Tasks
## Getting to know Git and Github
1. Create an account on Github
2. Fork this repository
3. Clone the forked repository to your computer 
4. Modify the src/index.jsx to print "hei maailma!" instead of "hello world!"
5. Save the changes to Github

## React
TODO weatherapp stuff here


## Run this application using Heroku
1. Install [heroku cli](https://devcenter.heroku.com/articles/heroku-cli)
2. Create new app to Heroku
    * [https://dashboard.heroku.com/new-app](https://dashboard.heroku.com/new-app)
3. Login to heroku on command line
    * *heroku login*
4. Add heroku remote to git configuration
    * *heroku git:remote -a \<app name\>*
5. Tell heroku to also install dependencies for development use
    * *heroku config:set NPM_CONFIG_PRODUCTION=false*
6. Tell our application to use port 80 instead of 8080
    * *heroku config:set PORT=80*
7. Push our code to heroku
    * *git push heroku master*
    
    
# Cheatsheet
## Saving changes to Github
```
git add <filename>
git commit -m "my first git commit"
git push
```
