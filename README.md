Authmap
======================

Provides the authmap table and functions removed from from Drupal 8.x and
inherited by Backdrop Core. This module is often used with other modules
providing Single Sign-On (SSO).

Requirements
------------

None

Installation
------------

- Install this module using the official Backdrop CMS instructions at
  https://backdropcms.org/guide/modules.


Documentation
-------------

This is a developer module. It creates the `authmap` database table removed
by Backdrop Core. See the discussion here:
https://github.com/backdrop/backdrop-issues/issues/2377.

* `user_get_authmaps` is now `authmap_get_authmaps`
* `user_external_load` is now `authmap_external_load`
* `user_set_authmaps` is now `authmap_set_authmaps`
* `user_external_login_register` is now `authmap_external_login_register`


Issues
------

Bugs and Feature requests should be reported in the Issue Queue:
https://github.com/backdrop-contrib/authmap/issues.


Current Maintainers
-------------------

- [Joel Steidl](https://github.com/joelsteidl).
- Seeking additional maintainers.

License
-------

This project is GPL v2 software.
See the LICENSE.txt file in this directory for complete text.
