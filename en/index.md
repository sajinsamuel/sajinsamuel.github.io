# Getting Started with MDwiki


## Section 1
### How to setup a public website using MDwiki and Github:

* Fork off this repository from github https://github.com/exalted/mdwiki-seed.

* Unzip the forked repository and find the ll_cc directory.

* ll_cc (List of languages and country codes) : Duplicate this directory and rename it to ‘en’ to create a markdown page in english. (en_us- English US, en-gb - British English).

* Open the index.html file with a text editor and find where it says "Override ll_CC below with your default language and country code".

* Change refresh meta tag from url=ll_CC/ to url=en/ (trailing / is very important)



## Section 2
###Hosting on Github:

* Create a new repository on github and name the repository like this "<your username>.github.io".

* Commit and push the files inside the forked repository.

* Open any browser and enter this link https://<your username>.github.io/en/#!index.md


[Click here to check the official docs](http://dynalon.github.io/mdwiki/#!tutorials/github.md)

[Click here to check the Quickstart guide by MDwiki](http://dynalon.github.io/mdwiki/#!quickstart.md)
