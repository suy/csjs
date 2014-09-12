csjs
====

Some examples using client side JavaScript with some frameworks (well, just
Backbone for now, but with extensions like LayoutManager or Marionette, since
Backbone alone is ridiculously under featured).

Notes
=====

Language
--------

http://javascriptweblog.wordpress.com/2010/06/07/understanding-javascript-prototypes/

http://www.artandlogic.com/blog/2012/07/prototypal-vs-functional-inheritance-in-javascript/

http://trephine.org/t/index.php?title=Understanding_the_JavaScript_new_keyword

http://trephine.org/t/index.php?title=JavaScript_classes

http://trephine.org/t/index.php?title=Simple_prototypal_inheritance

http://docs.closure-library.googlecode.com/git/local_closure_goog_base.js.source.html

https://developers.google.com/closure/library/docs/introduction

http://prototypejs.org/learn/class-inheritance

http://bolinfest.com/javascript/inheritance.php



### Backbone specific OOP with extend
http://blog.rjzaworski.com/2012/02/backbone-js-inheritance/

https://coderwall.com/p/xj81ua

http://blog.usefunnel.com/2011/03/js-inheritance-with-backbone/

http://www.erichynds.com/blog/backbone-and-inheritance

http://stackoverflow.com/questions/13105574/extend-using-underscore-vs-backbone

But beware, because even if some of those posts mention the existence of
`__super__`, the creator of Backbone and CoffeeScript only placed it there to
ease the lives of CoffeeScript developers. So `__super__` is not supposed to be
there. https://github.com/jashkenas/backbone/pull/787

Basics
------

http://learn.jquery.com/events/introduction-to-events/


Misc
----
http://todomvc.com/

https://github.com/addyosmani/backbonejs-gallery

http://glyphsearch.com/

http://www.blacktie.co/demo/counter/

Bootstrap
---------

http://bootstraptour.com/

http://ruby.bvision.com/blog/please-stop-embedding-bootstrap-classes-in-your-html

http://www.smashingmagazine.com/2013/03/12/customizing-bootstrap/

http://getbootstrap.com/examples/theme/

https://github.com/twbs/bootstrap/issues/12783

https://github.com/twbs/bootstrap/pull/13772

http://stackoverflow.com/questions/21301316/how-to-bootstrap-navbar-static-to-fixed-on-scroll

http://www.bootply.com/107973

https://github.com/twbs/bootstrap/pull/13904

[Sass/Less Comparison](https://gist.github.com/chriseppstein/674726)

Backbone
--------

### General

http://addyosmani.github.io/backbone-fundamentals/

http://ricostacruz.com/backbone-patterns/

**Excellent**
https://github.com/tbranyen/backbone.layoutmanager/wiki/Overview

https://backbone-patterns.heroku.com/

http://lostechies.com/derickbailey/2011/09/15/zombies-run-managing-page-transitions-in-backbone-apps/

http://dailyjs.com/2013/04/04/backbone-tutorial-16/

### Examples

http://coenraets.org/blog/2012/02/sample-app-with-backbone-js-and-twitter-bootstrap/

### Problems

* ["Backbone is a bit unique in that its best documentation is its source."](https://github.com/jashkenas/backbone/issues/3205)
* [The many uses of Model#toJSON](https://github.com/jashkenas/backbone/issues/2134)
* [The documentation was wrong till
  2013](https://github.com/braddunbar/backbone/commit/7f24896e4f90106587b5fd2ef3d7507de0d04826)

### On event systems, jQuery, etc.

https://github.com/jashkenas/backbone/commit/7dbfecc6c12f962455ad34ed87b8af954d05db82#diff-0d56d0d310de7ff18b3cef9c2f8f75dcR98

Marionette
----------

### Examples

http://dmytroyarmak.github.io/marionette-contact-manager/
http://dmytroyarmak.github.io/codeangels-marionette-introduction/

### Managing the views
http://www.smashingmagazine.com/2013/02/11/introduction-backbone-marionette/

http://lostechies.com/derickbailey/2012/03/22/managing-layouts-and-nested-views-with-backbone-marionette/

### Dependencies

This is in the source code. So the way one type might depend on the other might
be this.

```
// @include ../../tmp/backbone.babysitter.bare.js
// @include ../../tmp/backbone.wreqr.bare.js

// @include ../marionette.helpers.js
// @include ../marionette.triggermethod.js
// @include ../marionette.domRefresh.js

// @include ../marionette.bindEntityEvents.js

// @include ../marionette.callbacks.js
// @include ../marionette.controller.js
// @include ../marionette.region.js
// @include ../marionette.regionManager.js

// @include ../marionette.templatecache.js
// @include ../marionette.renderer.js

// @include ../marionette.view.js
// @include ../marionette.itemview.js
// @include ../marionette.collectionview.js
// @include ../marionette.compositeview.js
// @include ../marionette.layout.js

// @include ../marionette.behavior.js
// @include ../marionette.behaviors.js

// @include ../marionette.approuter.js
// @include ../marionette.application.js
// @include ../marionette.module.js
```
