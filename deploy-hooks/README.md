# Deploy Hooks

Heroku allows you to ping a url after deploying (https://devcenter.heroku.com/articles/deploy-hooks#http-post-hook), but it only allows you to set one. The task is to create an app to solve this problem, in broad terms it will accept a POST request and then make POST requests to one or more urls that have been configured.

## Requirements

Create a URL for heroku to POST to
Add / Remove the urls to ping
Accept POST from heroku and make the relevent POST requests
