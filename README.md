# compare

web tool to compare similar stuff

similar to socialcompare.com, vschart.com, diffen, ...

Requirements :
* define a tree list of features (functions), can be seen as the table of contents of a book
  * describes as code, short label (display), multi-line description with markup
  * incremental definition : can easily re-arrange the tree
* list of solutions and how they implement features
  * yes/no/may/n-a (scoring), a short label, a multi-line description with minimal markup for links, code blocks and bullets
* work in grid mode, can transpose fcts/sols as rows/cols depending on expected view point
* can be fully handled with keyboard only (menus, shortcuts) 
* can display multiple levels of features or zoom within
* can hide/show some functions and some solutions : hide/show all, flip

History :
* 1999-2000 : write as html/js-asp/vb-xml using xml files as backend
  * all ui is built in html/js, use xmlhttprequest from ie5 to read/write data
  * the asp/vb code is only returning xml data from the files and updating xml files from url encoded post data
  * one xml file per compared stuff (all features and solutions)
  * hosted on some free asp hoster
* 200x : rewrite as html/js-php-mysql hosted on free.fr
* 200x : tentative to rewrite on google appengine (python-google db)
* 2013 : optimize the ui part, using local wamp installation : more keyb commands, transpose, easier filtering
* 2015 : rewrite as html/js over github api and yaml files
