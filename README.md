Splitter
===

[Demo](http://andrienko.github.io/splitter/)

Splitter is a small JS script with no dependencies to create containers splitted horizontally or vertically
with moveable splitter bar.

It should work in modern browsers and even in IE8

(According to [this site](http://www.netmarketshare.com/browser-market-share.aspx?qprid=2&qpcustomd=0), when the code of
this script was written in April of 2014 the market share of IE8 was 20% amongst ALL browsers, which means that 1/5 of
mankind still used it, so I sacrificed some performance)

Usage
---

Add css and js files to your project:

    <script type="text/javascript" src="splitter.js"></script>
    <link rel="stylesheet" type="text/css" href="splitter.css"/>

Then add horizontally_divided or vertically_divided class to the element you want splitted

        <div class="vertically_divided">
            <div>Left</div>
            <div>Right</div>
        </div>

The element you are adding the class to must have two first-level div elements in it, which will become left
and right parts of split container

Changing appearance
---

The splitter appearance is defined in splitter.css file (which source is style.less). You can add whatever style
you wish to anything.

Minified version
---
Sometimes I make it using [a website](http://closure-compiler.appspot.com/home) (because I'm lazy and also I work on
three different environments and also because I'm lazy). I dont do this wery often and most likely the minified version
is not the recent.