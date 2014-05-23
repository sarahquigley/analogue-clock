Analogue Clock
==============

Old school time keeping.

View live version: [Analogue Clock Live](http://sarahquigley.github.io/analogue-clock/)

## What is Analogue Clock?

Analogue Clock is an experiment in CSS3 transforms and animations, an analogue clock made digital.

## How does it work?

### Turning the hands

CSS3 transforms and animations are used to animate clock hand rotations.

### Setting the time

Current time is detected using Javascript. Javascript templating (Mustache) creates a stylesheet that sets initial hand positions to the current time. 

### Keeping time

CSS3 animations keep time until the window looses focus. However, since CSS3 animations are paused when a window is out of focus, Javascript / Mustache tamplating resets clock hands to correct positions when window is returned to focus. 

## Supported Browsers
Chrome, Firefox 5+, IE 10+, Opera 12+, Safari 4.0+.
