**Version 3.0.1**
* Add `complete` methods that take the current operation as a parameter.

**Version 3.0.0**
* Migrated plugin to Grails 3.x.

**Version 0.2.4**
* Change the errorCode property to a text database column type.

**Version 0.2.3**
* Added missing bits for resolutionCode introduced in 0.2.2.

**Version 0.2.2**
* Added resolutionCode to the standard task payload.

**Version 0.2.0**
* Persistent tasks no longer automatically save after the various updating methods are run.
* Persistent tasks no longer store a domain instance for the object lifecycle. Domains are now loaded, saved, and discarded.
* Domain interaction happens within new sessions to ensure that operations occur outside of transactions.
