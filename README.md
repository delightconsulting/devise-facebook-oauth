# Facebook Authentication with Devise

## Blog Post
[Blog Post](http://www.delight.consulting/blog/facebook-authentication-with-devise/)

## Setup
```bash
$ git clone git@github.com:delightconsulting/devise-facebook-oauth.git
$ cd devise-facebook-oauth/ && bundle install
$ rake db:migrate
$ figaro install
```

Replace the contents of your `config/application.yml` with:
```
development:
  FACEBOOK_APP_ID: "YOURFACEBOOKAPPID"
  FACEBOOK_APP_SECRET: YOURFACEBOOKAPPSECRET
```
