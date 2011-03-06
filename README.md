# Bassline

A basic SASS baseline to start projects with. Really simple.

## INCLUDES

* Reset (Based on Eric Meyer's but with HTML5 elements included)
* Base (basic html + typography)
* Lists
* Tables
* Form Elements
* Some Variables & Mixins

## USAGE

    cd /path-to-stylesheets
    git clone git@github.com:michaelparenteau/bassline.git
    gem install sass
    sass --watch stylesheets/bassline:stylesheets
    
**NOTE:**

* Make sure you define the _variables.sass file to your liking.
* Be sure to look at the _mixins.sass file for what is available. This will change as time goes on.
* Do NOT edit the screen.css file. When you `sass --watch stylesheets/bassline:stylesheets` this will override the file with sass changes
* To output different styles of css file (ie: dev, production, or preffered formatting):

    # there are 4 types of output: nested, expanded, compact, compressed
    sass --watch stylesheets/bassline:stylesheets -t [output-style-here-minus-square-brackets]

## Resources

* For more info on SASS - [http://sass-lang.com/](http://sass-lang.com/)
* For a more complete SASS Framework - [http://compass-style.org/](http://compass-style.org/)

## Fin

Bassline is a work in progress. It is good enough to start with for me & also allows for me to learn more about SASS. It is not a competitor or replacement of compass! Compass is a _very_ thorough framework. Bassline will change as I learn more. If you have good suggestions and would like to share them, please do!