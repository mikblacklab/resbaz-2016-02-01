# Dunedin ResBaz-2016 Fork

This is a fork of the main ResBaz-2016 website repo:

https://github.com/resbaz/resbaz-2016-02-01

It has been tweaked so that a live version can be seen on github.io, so that the impact of edits can be checked prior to update to main site.  This requires changing the _config.yml file to get jekyll working properly on githib.io. I also deleted the CNAME file (which sets the website url) because it gives a build warning (and sends me an email) every time a commit is made. As a result, we can't easily submit pull requests back to the main repository, because the changes will include alterations to files that we don't want to change. 

My suggestion is that we _ONLY_ edit the file relating to the Dunedin page of the website:

https://github.com/mikblacklab/resbaz-2016-02-01/blob/gh-pages/_posts/2016-02-01-dunedin.html

and then I will periodically transfer these edits to the main repo and submit a pull request to Bill.

This version of the Dunedin component of the site can be viewed at:

http://mikblacklab.github.io/resbaz-2016-02-01/dunedin/

Committing a change to the webpage file will trigger the site to be rebuilt, and then changes can be checked via github.io link above.  There can be a considerable (and frustrating) lag between commit and build, so it can take a while for changes to propagate to the live version.  And occassionally the build process will time out so that the live version does not reflect the current version of the repo.  

Also, in some cases formatting issues (e.g., the "schedule" table on the Dunedin page) cause problems with the build so that jekyll doesn't create the html page for serving up on github.io.  In that case you have to go bug hunting (or revert) until you've identified the issue and got the page to build again.

_Note:_ Because of how the map info is rendered on the front page (http://mikblacklab.github.io/resbaz-2016-02-01), the links are hardcoded, so clicking on the Dunedin link actually takes you to the Dunedin page of the live resbaz website (https://feb2016.resbaz.com/dunedin/), rather than the copy relating to this repo.  This can be fixed, but it involves editing more files that we don't want to submit pull requests for, so I think it's easiest to just look directly at the Dunedin page (http://mikblacklab.github.io/resbaz-2016-02-01/dunedin/) rather than trying to navigate to it from the front page. 
