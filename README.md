# Ionic Rails Backend Template

A simple and opinionated Rails application template to bootstrap a backend for your Ionic (or any mobile) app. Forget Firebase, roll your own. Includes token authentication that's fully ready to be a backend for your Ionic app.


## Create a Backend

```
rails new my_ionic_backend -m https://raw.githubusercontent.com/seeingidog/ionic_rails_backend_template/master/template.rb
```


## Deployment

### Heroku

Applications created from this Rails Template is ready to deploy to Heroku off the shelf in the normal manner:

```
heroku create
git push heroku master
heroku run rake db:migrate
```





## Contributions
Please add to this or the example backend app.



### Future/Requests for pull requests
* Ionic plugin to make API calls to backend as easy as Firebase is to drop in.
* More flexibility for mobile developers by allowing arbitrary writes to a key-value store? (à la Firebase)


