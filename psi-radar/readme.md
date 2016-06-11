# Technology Radar

A simple technology radar map (made famous by [Thoughtworks](http://www.thoughtworks.com/radar)).

> ##[Demo](http://urre.github.io/radar)

## Make your own radar

Fork/clone this repo

	git clone git@github.com:urre/radar.git

### Add user info

Edit ``user.json``. This is displayed in the header showing your Gravatar and your name with a link to Twitter. You can also specify your custom header image. Try a nice one from [Unsplash](http://unsplash.com).

	{ "user":
	    [
	        {
	            "name": "Urban Sandén",
	            "email": "hej@urre.me",
	            "website": "http://urre.me",
	            "background": "https://unsplash.imgix.net/photo-1418479631014-8cbf89db3431?fit=crop&fm=jpg&h=700&q=75"
	        }
	    ]
	}

### Add blips

Edit ``blips.json`` like this. Areas: techniques, tools, frameworks, platforms. Statuses: hold, assess, trial, adopt.

	{ "blips":
	    [
	        {
	            "title": "Node.js",
	            "area": "platforms",
	            "status": "trial",
	            "link": "http://nodejs.org"
	        },

### Publish

+ Publish using [Github Pages](https://pages.github.com/) by using the ``gh-pages`` branch.
+ Fire up a browser and go to http://yourusername.github.io/radar

Or simply just host it on your own server.

### Changelog

#### 1.2.0
+ New color scheme, new default background svg image
+ Use user website instead of Twitter profile url

#### 1.1.0
+ Added possiblity to add custom header image
+ Added layout switcher and list style for smaller screens
+ Blip hovering from the lists

#### 1.0.0
+ First version published

### License
Copyright (c) 2014 Urban Sanden. Licensed under the MIT license.
