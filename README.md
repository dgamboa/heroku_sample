# Heroku Deployment Tutorial from Udacity

Key Lessons Learned:
* working inside of other directories can create issues deploying to Heroku
* Udacity's sample files often lack the necessary modules so be sure to check those

Deployed sample app [lives here](https://hk-dg-sample.herokuapp.com/)

## Endpoints

The app has two simple endpoints:
* "/"
* "/coolkids"

Both of these return simple text outputs. The index endpoint will add exclamation marks if the environment variable `EXCITED` is set to **true** 
