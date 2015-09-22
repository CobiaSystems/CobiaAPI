API Documentation
===

This is a REST-style API that uses JSON for serialization and OAuth for authentication.

Making a request
----------------

* All URLs are prefixed with `/rest/`
* Any URLs with `/rest/admin/` will require a session that has been authenticated
* Any URLs with `/rest/public/` are publically available, and do not require authentication
* For more information, review the [Guide: Rest Style and Structure](https://github.com/CobiaSystems/api/wiki/Guide:-Rest-Style-and-Structure)
Authentication
--------------

Read the [Authentication Guide](https://github.com/CobiaSystems/api/wiki/Authentication-Guide) to get started.

Errors
------

Errors are handled by a returned Status code NOT equal to 1, for example, 0 or 302. 

API
-----------------------

* [Account](https://github.com/CobiaSystems/api/wiki/Account)


Guides
-----------------

* [Adding Competitors](https://github.com/CobiaSystems/api/wiki/Guide:-Adding-Competitors)
* [Logging In](https://github.com/CobiaSystems/api/wiki/Guide:-Logging-In)

Help us make it better
----------------------

Please tell us how we can make the API better. If you have a specific feature request or if you found a bug, please use GitHub issues. Fork these docs and send a pull request with improvements.
