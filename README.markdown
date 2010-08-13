# The protogé of OProto: OProtoJ
**First, get the gist [here](http://github.com/ericdfields/OProto).**

OProtoJ is a prototype bootstrapping framework that relies on HTML, jQuery and a little tiny bit of [SASS](http://sass-lang.com)/[Compass](http://compass-style.org/) magic.

## Why not use OProto?

[OProto](http://github.com/ericdfields/OProto) relies on Rails, StaticMatic, Haml. While totally awesome, it can be overkill where all you need is a HTML skeleton and a few jQuery libraries.

## So what does OProtoJ offer instead?

Plain and simple HTML5 markup and goodies based off of the [HTML5 Boilerplate](http://html5boilerplate.com/), workable stylesheets, and SASS for the adventurous.

## So to get this up and running, all I need to do is check it out, mark up some html files, and modify screen.css?

Yes, exactly.

    $ git clone git://github.com/ericdfields/OProtoJ.git my_project
    
And you're done.

## And if I want to use SASS and/or Compass I just need to tell it to watch my project directory, right?

Right again.

Of course you have to have compass installed:

    $ sudo gem install comapss
    
And then, like you said, have compass watch your project.

    $ compass watch my_project
    
## And if I'm doing that, I just need to work my Sassy CSS files, save, and Compass will automatically compile them to the stylesheets directory, right?

Hey, you're getting the hang of this! Yeah, totally. Those can be found found in the *src* directory.

## So how about HTML templates, includes, jQuery widgets? What do I have to work with?

*index.html* shows you how to load some content in another html file.

The *_index.html* partial shows you how to load a jQuery widget or two.

## Sass and Compass sound really cool. Where can I read up on those in order to make the most of them?

[Here](http://sass-lang.com) and [here](http://compass-style.org/), respectively.

Don't forget that Compass comes bundled with mixins for the Blueprint CSS framework. [Spend some time reading](http://compass-style.org/docs/reference/blueprint/) how you can mix Blueprint into your Sass.

## Anything else I should know?

Created by Eric D. Fields, Senior UX Developer at Optaros

Copyright Optaros

Dual licensed under MIT and GPL