portlet-style-guide
===================

Proof of concept of a code-guide style style guide for portlet development.


Vision
======

Scope
-----
The `portlet-style-guide` will advise about developing portlets, suggesting `CSS` and markup usages, caching practices, API usages, etc., that will make the portlet thrive in our portal.

Examples of in-scope topics:
* Producing markup that plays nicely in a portal
* Using CSS styles that play nicely in a portal
* Namespacing your JavaScript to play nicely in a portal
* UI conventions to look good and be highly usable in the portal
* Versioning, Maven build, and especially entity file practices *as they relate specifically to playing nicely in the portal*


Not in scope
------------
This is *not* a general Java development style guide and is not intended to comment on anything that's not particularly about developing a *Portlet*.

Examples of not-in-scope topics:
* Using the right kind of whitespace in your source code
* How to name your Java classes
* Excellent source control commit message formatting practices

portlet-style-guide and portal-style-guide
-------------------------------------------
Current vision is to have complementary `portlet-style-guide` and `portal-style-guide` projects, so that developers of a portlet intended to build a webapp not delivered as part of the portal `.war` itself can have a style guide focused on that need.

The `portal-style-guide` would include by reference the `portlet-style-guide` and then work from there advising about what's special about developing in the portal infrastructure.


Acknowledgements
=================

Inspired by [Code Guide](http://mdo.github.io/code-guide/).

See also `ACKNOWLEDGEMENTS.md` accompanying.
