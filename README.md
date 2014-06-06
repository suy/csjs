csjs
====

My Client Side JavaScript tests

Notes
=====

Basics
------

http://learn.jquery.com/events/introduction-to-events/


Misc
----
http://todomvc.com/

http://bootstraptour.com/

http://ruby.bvision.com/blog/please-stop-embedding-bootstrap-classes-in-your-html

https://github.com/addyosmani/backbonejs-gallery


Backbone
--------

### General

http://addyosmani.github.io/backbone-fundamentals/

http://ricostacruz.com/backbone-patterns/

**Excellent**
https://github.com/tbranyen/backbone.layoutmanager/wiki/Overview

https://backbone-patterns.heroku.com/

http://lostechies.com/derickbailey/2011/09/15/zombies-run-managing-page-transitions-in-backbone-apps/

### Examples

http://coenraets.org/blog/2012/02/sample-app-with-backbone-js-and-twitter-bootstrap/


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
