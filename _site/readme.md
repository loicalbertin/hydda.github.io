# Site Web du projet HYDDA

[![Build Status](https://travis-ci.org/occiware/occiware.github.io.svg?branch=master)](https://travis-ci.org/occiware/occiware.github.io)


Project's web site: [https://hydda.github.io/](https://hydda.github.io/)  

This repository contains the sources for HYDDA's community web site.  
On every commit, a [routine](http://jekyllrb.com/) is executed. It generates static HTML files and host 
them on [GitHub pages](https://pages.github.com/).

To build the web site locally, you must install [Jekyll](http://jekyllrb.com/).    
Then, use...

	bundle exec jekyll serve -w

... to run a web server locally, or... 

	bundle exec jekyll build

... to simply generate static HTML files.  
When using Jekyll on your own machine, you may have errors about missing gems or dependencies.

	sudo gem install jemoji
	sudo gem install github-pages

You will find more information on [Github's web site](https://help.github.com/articles/setting-up-your-pages-site-locally-with-jekyll/).	
