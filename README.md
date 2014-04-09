meteor0.8.0-ie8-bug
===================

This is a reproduction of the stack overflow infinite loop bug that occurs in internet explorer 8 with the Meteor 0.8.0 release.

This bug occurs on live sites but not when run on localhosts. Enclosing a handlebars helper or handlebars template inside of div tags, or enclosing them as an attribute within a tag creates the error.

http://rainbough-ie8test.meteor.com/


Other Notes:
============

If you try this with the modernizr-meteor package the error changes to an "exception thrown and not caught error."