0.2 (2013-04-30)
----------------
- Add documentation.

0.1.2 (2013-04-24)
------------------
- Make the library easier to depend on by not pinning the versions
  of all our indirect dependencies.

0.1.1 (2013-04-23)
------------------
- Fix a crash with Facebook auth because its response is not JSON.

0.1 (2013-04-23)
----------------
- Initial release with code from Yith Library Server
- License change with the agreement of original YLS copyright holders
- Make the scope configurable
- Make the [google,facebook]_callback views return the result of
  a configurable callback function.
