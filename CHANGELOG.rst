CHANGELOG
=========

0.3.0
-----

 - Repackaged as `envparse2` to be able to install on newer versions of Python.


v0.2.0
------

- Major rewrite, based on django-environ but made agnostic.
  - Tox support for running tests with different Python types.
  - Use pytest for unit tests.


v0.1.6
------

- Use curly-braces for proxied values since shells will attempt to resolve
dollar-sign values themselves. Dollar-sign style is still supported, but
deprecated and will be removed in a 1.0 release.
