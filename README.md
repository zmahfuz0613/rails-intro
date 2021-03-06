# Intro To Ruby on Rails

_Introduction_

For this weekend's homework you will work through roughly the first half of the Ruby on Rails `Getting Started` documentation.  This tutorial is _very_ well constructed and has sheperded many new developers through the basics of the Rails framework.  Rails is a large, opinionated framework so it will take some time to get accustomed to; that said, the "Rails way" favors convention over configuration which makes it especially easy to get up and running with a minimum amount of setup.

*Important Notes:*

The guide introduces Rails views with `erb` templates which provides the same functionality as does JSX in React in that you can now execute Ruby code within the HTML. The main focus of the Rails unit will be building a full-stack app using a Rails server and React client.  Yes, it is a bit of a slip to have to use erb just once while learning a bunch of new stuff.  Fortunately, the `erb` parts of the homework are very minimal.  If you want, go ahead and just paste in the `erb` code, but be sure to actually type out the rest.  The only significant `erb` part is the form. The payoff for dealing with this slight inefficiency is being able to get a more direct introduction to controllers, routes, and models which are the meat of Rails anyway.

As of Rails 6.0, we need `yarn` to work with Rails, so if you haven't already, run `brew install yarn`.
In addition, substitute the `rails new blog` with `rails new blog -G --database=postgresql` when you create the app.

### Deliverable

The ruby blog tutorial up to and including Section 5.8

### Get Going

Navigate to the link below and *complete the tutorial at least up through Section 5.8 "Listing all articles"*.  The sections after 5.8 begin to involve Rails views more comprehensively and thus present less direct value for us at the moment.  Of course, feel free to continue if you wish; just know that we'll focus on the routing/controllers and models parts of the framework.

[So here's the link](https://guides.rubyonrails.org/getting_started.html)
