# Intro To Ruby on Rails

_Introduction_

For tonight's homework you will work through roughly the first half of the Ruby on Rails `Getting Started` documentation.  This tutorial is _very_ well constructed and has sheperded many new developers through the basics of the Rails framework.  Rails is a large, opinionated framework so it will take some time to get accustomed to; that said, the "Rails way" favors convention over configuration which makes it especially easy to get up and running with a minimum amount of setup.

*NB:*

The guide introduces Rails views with `erb` templates (fwiw, they are quite similar to `ejs` templates so the syntax should feel familiar), but this will almost certainly be the last time you use `erb` during WDI.  The main focus of the Rails unit will be building a full-stack app using a Rails server and React client.  Yes, it is a bit of a slip to have to use erb just once while learning a bunch of new stuff.  Fortunately, the `erb` parts of the homework are very minimal.  If you want, go ahead and just paste in the `erb` code, but be sure to actually type out the rest.  The only significant `erb` part is the form; the rest is fairly similar to `ejs`.  The payoff for dealing with this slight inefficiency is being able to get a more direct introduction to controllers, routes, and models which are the meat of Rails anyway.

### Submitting

The aforementioned Rails Guide takes you from the very start of installing Rails all the way through building out a simple blog application.  Since Rails by default initializes a `git` repo when starting a new project, the workflow for submitting tonight's homework will be a little different.  
	- After following the tutorial, commit your code.
	
	- Then make a `new repository` on github enterprise.
	
	- run `git remote add origin <github enterprise repo url>`
	
	- Push your code to origin
	- Finally, make an issue ticket on this repo with a link to the repo you made in the previous step.

### Get Going

Navigate to the link below and *complete the tutorial at least up through Section 5.8 "Listing all articles"*.  The sections after 5.8 begin to involve Rails views more comprehensively and thus present less direct value for us at the moment.  Of course, feel free to continue if you wish; just know that we'll focus on the routing/controllers and models parts of the framework.

[So here's the link](https://guides.rubyonrails.org/getting_started.html)
