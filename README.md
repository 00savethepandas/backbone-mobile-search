
A sample Backbone app with native routing (something tricky to achieve when using Backbone in combination with jQuery mobile).

**Uses:**
- Backbone.js for MVC
- Underscore.js for Micro-templating and utilities
- jQuery Mobile
- LABjs for script loading
- Flickr API for data

**Why is this worth checking out:**

This is one of the first Backbone sample projects (I've seen) to include information on how to override jQuery Mobile's standard routing so that your app can still make use of all of Backbone's native routing goodness without having to hack up jQMobile directly (an issue a large number of developers run into regularly).

**Current status:**
Being heavily refactored and re-written. Bookmarking has been fixed since the last version, however mobile Safari support is broken until I decide whether to maintain a single all-in-one view for search/results or introduce multiple views.