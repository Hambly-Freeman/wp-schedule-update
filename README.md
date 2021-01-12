WordPress Schedule Update
====================

A simple Wordpress Plugin to Schedule Content Updates

Motivation
----------

These days Wordpress is scarcely used as a pure blog. Most of the time it is used as a full-blown CMS with many
additional requirements. Especially the publishing workflow for posts and pages as well as their changes becomes
demanding. Using plugins like visual composer or advanced custom fields with their flexbox addon it becomes common to
build huge startups, subsides and languages using a simple, understandable visual editor instead of bolting them
together using custom post types. If this is a good and DRY way to go is not to discuss here :)

A Problem arises as soon as you try updating such a complex single page at a specific date in the future - there is no
easy way so schedule changes to already published wordpress pages inside the wordpress core functionality. Existing
plugins that try to tackle this problem are often far from a feature complete and try to re-use the revision system. The
experience we made with our customers showed, that the revisions approach is hard to grasp for less technical users and
also rather error prone.

These are the main reasons for us to brew our own solution.

Features
--------

WordPress Schedule Update change is a minimal plugin. It only does one thing, but tries to do this the right way: Take a
copy of an arbitrary post/page/cpt, change it and make it replace the original post at a given date and time in the
future.

Installation
------------

Like every Wordpress plugin either place it in wp-content/plugins or use the integrated plugin installer.


