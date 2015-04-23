# compare

web tool to compare similar stuff

work in grid mode, define a tree list of features, list of solutions and how they implement features : yes/no/may/n-a, a short label, a multi-line description with minimal markup for links

similar to socialcompare.com

* 1999-2000 : write as html/js-asp/vb-xml using xml files as backend
  * all ui is built in html/js, use xmlhttprequest from ie5 to read/write data
  * the asp/vb code is only returning xml data from the files and updating xml files from url encoded post data
  * one xml file per compared stuff
  * hosted on some free asp hoster
* 200x : rewrite as html/js-php-mysql hosted on free.fr
* 200x : tentative to rewrite on google appengine (python-google db)
* 2013 : optimize the ui part, using local wamp installation : more keyb commands, transpose, easier filtering
* 2015 : rewrite as html/js over github api and yaml files
