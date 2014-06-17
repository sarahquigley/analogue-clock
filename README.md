Analogue Clock
==============

Old school time keeping.

View live version: [Analogue Clock Live](http://sarahquigley.net/analogue-clock/)

## What is Analogue Clock?

Analogue Clock is an experiment in CSS3 transforms and animations, an analogue clock made digital.

## How does it work?

### Turning hands

CSS3 transforms and animations are used to animate the rotations of the clock hands.

### Setting time

The current time is detected using Javascript. Javascript templating (Mustache) creates a stylesheet that sets the initial angles of the clock hands to the current time. 

### Keeping time

CSS3 animations keep time until the window looses focus. However, since CSS3 animations are paused when a window is out of focus, Javascript / Mustache templating resets the clock hands to the correct angles when the window is returned to focus. 

### Totally responsive

I use vw and vh units and a single media query to create a beautifully responsive clock that resizes gorgeously with both browser width and height. There's a fallback to percentage units for browsers that don't support these units, which gives an almost but not quite as beautifully responsive result.

## Why did you make this?

Of course, potential uses of this are endless. CSS powered wrist watch displays and time travel are just two of the exciting possibilities.

But seriously, I made this for joy and for learning's sake. Plus, I'm hoping you've gotten a kick out of my little project - and maybe even learned something... Thanks for indulging a little old school time keeping!

## Supported Browsers
Chrome, Firefox 5+, IE 10+, Opera 12+, Safari 4.0+.
