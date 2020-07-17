### apptky1 | heroku Startup test apps
---

git clone git@github.com:takagotch/apptky1.git
cd apptky1
heroku create apptky1
git push heroku master
heroku open

###### apptky1
```
index.php | <?php include_once("home.html"); ?>
composer.json | {}
README.md
home.html | ...
cmd.sh
```
```
###### Steps
Add a file called composer.json to the root directory by running touch composer.json
Add a file called index.php to the root directory by running touch index.php
Rename the homepage (e.g. index.html) to home.html
In index.php, add the following line: <?php include_once("home.html"); ?>
In composer.json, add the following line: {}
Run git push heroku master
Done! Visit your deployed single-page website, hosted by Heroku (as a fake PHP app ☺).
```



---
---

#### StartupPages every programing lng.
---
https://devcenter.heroku.com/articles/buildpacks#officially-supported-buildpacks

ex.
###### ruby | apptky2
https://elements.heroku.com/buildpacks/heroku/heroku-buildpack-ruby



```
```


```
```
