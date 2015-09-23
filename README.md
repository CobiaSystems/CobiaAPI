API Documentation
===

This is a REST-style API that uses JSON for serialization and OAuth for authentication.

Making a Request
----------------

* All URLs are prefixed with `/rest/`
* Any URLs with `/rest/admin/` will require a session that has been authenticated
* Any URLs with `/rest/public/` are publically available, and do not require authentication
* For more information, review the [Guide: Rest Style and Structure](https://github.com/CobiaSystems/api/wiki/Guide:-Rest-Style-and-Structure)

Errors
------

Errors are handled by a returned Status code NOT equal to 1, for example, 0 or 302. 

API
-----------------------

* [Account](https://github.com/CobiaSystems/api/wiki/Account)
* [Premium](https://github.com/CobiaSystems/api/wiki/Premium)


Guides
-----------------

* [Logging In](https://github.com/CobiaSystems/api/wiki/Guide:-Logging-In)
* [Adding Competitors](https://github.com/CobiaSystems/api/wiki/Guide:-Adding-Competitors)

Feedback is Welcome
----------------------

Please let us know how the experience of using our API is. If you have a feature request or found a bug, you can create an issue on this repository. Alternatively, you can fork and create a pull request if you feel inclined to help the documentation.
