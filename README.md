### apptky1 | heroku Startup test apps
---
###### Steps
Add a file called composer.json to the root directory by running touch composer.json
Add a file called index.php to the root directory by running touch index.php
Rename the homepage (e.g. index.html) to home.html
In index.php, add the following line: <?php include_once("home.html"); ?>
In composer.json, add the following line: {}
Run git push heroku master
Done! Visit your deployed single-page website, hosted by Heroku (as a fake PHP app ☺).
https://devcenter.heroku.com/articles/buildpacks#officially-supported-buildpacks
###### ruby
https://elements.heroku.com/buildpacks/heroku/heroku-buildpack-ruby



```
```


```
```
