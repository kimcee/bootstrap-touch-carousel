
# Bootstrap TouchCarousel

A drop-in replacement for Twitter Bootstrap's Carousel (v3.00) to enable gestures on touch-enabled devices.


## Features

* Supported gestures: `dragleft` `dragright` `swipeleft` `swiperight`
* Build with Less & Grunt
* No extra initializations


## Quick start

1. [Download zip](https://github.com/ixisio/bootstrap-touch-carousel/archive/master.zip)
2. Clone the repo: `git clone git://github.com/ixisio/bootstrap-touch-carousel.git`
3. As a Bootstrap git submodule `git submodule add git://github.com/ixisio/bootstrap-touch-carousel.git /vendor/bootstrap-touch-carousel`


## How it works

This jQuery Plugin is designed to add touch-support to your existing bootstrap carousel. The only thing you have to do, is to load these to files:

```
/dist/js/bootstrap-touch-carousel.js
/dist/css/bootstrap-touch-carousel.css
```


## Live Demo

`examples/index.html`


## Compiling CSS and JavaScript

> Bootstrap uses [Grunt](http://gruntjs.com/) with convenient methods for working with the framework. It's how we compile our code, run tests, and more. To use it, install the required dependencies as directed and then run some Grunt commands.

[See twbs docs](https://github.com/twbs/bootstrap/blob/master/README.md)


## Future Tasks

* Endless Loops (cycle)
* Live Resize
* Hammer.js custom build (use only whats required)
* MSPointer: Support pointer and gesture events. Tests needed!
* Optimize indicator pills for touch
* Better Documentation
* Unit Tests (qunit)
* Without-Hammerjs Version


## Copyright and license

Copyright (c) 2013 ixisio Licensed under the MIT license.
