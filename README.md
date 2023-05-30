# token_svg

A webpage to make generic round tokens (100px x 100px PNG files) for use on [owlbear rodeo](http://owlbear.app) or any other VTT or purpose, but I made it to support my need for quick off the cuff tokens that could be made visually distinct for owlbear.  

[Use it here.](https://nephlm.github.io/token_svg/index.html)

The generic tokens have a fill color (the center), ring color and text color.  The text can be 0-2 characters, so it can still be read.  The ring can be from 0px to completely filling the token.  

![screenshot](screenshot.png "User Interface")

Here are a few examples of the kind of token the page creates.

![screenshot](tokens.png "Examples")

* All values can be randomly and manually set.  
* There is code in place to generate complimentary colors between fill and ring/label.  While it helps in finding visually distinct colors, it's still fairly primitive.
* It uses no backend, but does use js libraries that are hosted on CDNs, so you can download the html page and run it locally, it still needs internet access at least the first time you load the page.  