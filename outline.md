One man's journey from Ruby to JavaScript

* This journey was by necessity



* My journey
  * When I first started programming I wanted to make visual things. Games, apps, sudoku solvers
  * I didn't really want to make command line apps
  * I grew to love solving problems on the command line, but my heart still ached for something more
  * Then I found web programming, which was _better_ but still pretty cruddy
  * SQL, backend stuff, to produce static HTML in PHP
  * Then I found ruby, and grew a love for backend stuff.
  * A language with no complexity, no IDE, no compiling, no weird, errors. Just fun!
  * But it still wasn't visual
  * JavaScript was the first inkling I had of building "real" applications
  * But man did it SUCK!
  * jQuery soup, no package management, no care
  
  * Then we started Float
  * Tried to build a spreadsheet, but with a rails backend, and no serious javascript code
  * Well, I say "no serious JavaScript code", it was serious, it was just half a megabyte of chaos
  * Then I found this book:
     [JWA]
  * And then I found BackBone, and fell in love, well let's say lust
  * And finally I fell in love with JavaScript
  * An insidious love, but love

* Main Lesson!
  * JavaScript is not just Ruby but with worse syntax and lots of global variables
  * JavaScript is a completely different paradigm
    * For building user interfaces
    * Asynchronous
    * Non-linear
    * Completely not like ruby
    * OMFG STATE!
  * This sucks! At first, we like writing top to bottom code
  * Stateful code is a bugger to write
  * But it's worth it, if we want to build the kinds of applications that our users want to use

  * Somebody is going to be writing a crap load of JavaScript for your applications
  * Do you want it to be some horrid, ad-hoc, unloved code that you "sprinkle" on at the end
  * Or do you want to OWN it, care for it, nurture it?

  * This is definitely _NOT_ to say that your job as a ruby developer is under thtreat, if anything your job as a ruby developer might get even better, as you can focus on the important backend business logic stuff, and not with the crappy view layer which has always been a horrible procedural mess.
  * _BUT!_ what I am saying is that there is this really exciting world of application development, which you undoubtedly already have some skills in, and which is really easy to get started, and only going to be _HUGE_ over the next few years, which you get your teeth stuck in to if you really want to!

* Okay, so let's get excited about JavaScript!
  * It's really not that bad a language
    * Okay it was obviously built in a weekend
    * And there are some cross browser issues, although thankfully they are going away now that we are in 2013
    * But under all that there's a really nice, simple, powerful language begging to be played with
    * And if you really hate it, there's always coffeescript

  * Browsers are now super, super awesome, and only getting better
    * Performance is actually pretty awesome
      * We can actually build Float/SpreadSheets in the browser
    * There is so much stuff we can play with now, that works really well
      * NyanCat? (webrtc)
      * Visualiser? (audio api)
    
* And let's get excited about building real applications
  * We aren't building websites any more, we are building applications
  * An application is a nice user interface for a user to interact, understand or otherwise experience his data
  * It's 2013, that better feel like an application, and not just a static website
  * Separation of concerns is awesome
    * We are splitting up our applications more and more to keep concerns isolated
    * Your front end and your back end applications talking to each other over some kind of wire protocol with a data transfer format!
    * The freedom that comes from knowing that you are just going to speak json between your apps is amazing

  * Applications are generally stateful, but Rails is stateless
  * This means a lot of wasted effort computationally and programmer complexity just to mimic a stateful application using rails
  * Client side applications embrace this statefullness
  * and this statefullness is a good thing
    * Your view layer is no longer just a dumb view of your data, it understands your data, can react and interact with it.
    * If you make a single change in a cell on a spreadsheet, that might affect everysingle cell on the page, or it might affect none, you don't really want to be talking to the server, and rerendering every cell on every change, because your view layer doesn't understand your data, do you?


* All in?
  * Don't panic, you don't have to go all in at once
  * you don't have to completely separate your front and backends
  * you can use the rails asset pipeline, and just keep your frontend as part of your app (Although i think this will change)
  * you don't need to worry about how your client apps will authenticate, etc, just keep it simple to start with
  * you can still use "dumb" rails views for the less "Appy" parts of your application (login, preferences, billing, etc)
  * But if your starting a fresh I would think about all these things seriously

* Rails?
  * rails is still an awesome application server
  * this does not need to be the end of rails by any stretch
  * I _HOPE_ DHH's view on this stuff doesn't turn people off rails, but I have hope (rails::api)

* The future?
  * The JavaScript world is still pretty immature, I'll grant you that, but it's growing up very fast
  * Tooling is getting better, testing is getting better, frameworks are getting better
  * In the last year angular and ember have gone from playthings to serious, solid frameworks with lot of "air time"
  * Backbone is still awesome if you know how to wield it
  * The next year or two is going to see lots of things shakeout I think, with all the current major frameworks hitting their 1.0 releases, and more and more applications embracing this stuff
  * Now is the time to start learning this stuff if you are at all intrigued. Learning new things is always going to be frustrating, and sure there are still some quirks, but client side applications are "production ready", and I implore you to at least have a play

* How would I learn?
  * If you haven't done much JavaScript beyond playing with some jquery I would just have a good hack around
  * get your head around the syntax, the object model (or lack thereof), of the more functional sides of JS (underscore)
  * really understand the asynchronous callback side of javascript
  * understand the dom (the object model behind html)
  * read the JWA book (it's not a full on reference guide, but basically a ground up explanation and building of a mvc framework similar to backbone for js apps which will get you up to speed on the concepts)
  * Rebuild the todomvc application in a few of the frameworks (angular, backbone, ember) to start to see what is going on
  * Care, craft, grow

* Lessons learned
  * JavaScript programming is fun when you treat it like you care about it
  * Things have come along way, and still have a long way to go but it's getting better
  * Browsers are super powerful (I can do what I got in to programming to do)
  * Separation of concerns
  * Asset pipeline is kinda hellish, but maybe ember will figure that out?
  * JavaScript programming is NOT ruby programming but in a different language



