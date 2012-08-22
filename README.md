ktween
======

There are already many tween engines out there and i recommend that you shouldn't use this one.

This engine is aimed for personal use and i can't ensure anything.

Another lightweight and fast tween engine...

#HOW TO USE

##Syntax : KTween.add(target, [time, delay, ease], props, [fComplete, p], [fUpdate, p], [fStart, p]);

* target : The Object whose properties need to be tweened
* time : The duration of the tween.
* delay : the delay time before the tween start (optional, default = 0).
* ease : Easing funtion applied to the tween (optional, default = null).
* props : Object contains the end properties needed to be tweened to
* fComplete : Function to be called when the tween finished
* fUpdate : Function to be called when the tween render
* fStart : Function to be called when tween start render the first time (mostly used with delay)
* p: parameters pass by when the function is called.
## FEATURES

* Lightweight : < 4kb
* Overlaps : Auto checking for overlap properties and remove them properly with the awareness of delay.
* Fast : not very fast, but rather fast
* Plug-in Architecture : Bezier + Tint with amount supported + Filters
* Simple : One line of code to tween. You don't need to pass parameters that you don't need, almost everything has default value to keep your typing down to minimum
* Multiple properties : Tween multiple direct properties of any object with only one line of code
* Time savings : Minimize the typing needed to create tweens but still keep the code clear and easy to read.

## DEMOS
[Offline]
speed test (1500 sprites) : http://kudostudio.net/googlecode/ktween/speed.html
align test (4000 sprites) : http://kudostudio.net/googlecode/ktween/align.html
bezier test : http://kudostudio.net/googlecode/ktween/bezier.html
tint test : http://kudostudio.net/googlecode/ktween/tint.html