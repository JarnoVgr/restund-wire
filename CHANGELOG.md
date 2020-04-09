# Changelog

## Version 0.4.12 - 2015-10-03 Alfred E. Heggestad <aeh@db.org>
* stat: add counter for CreatePermission request
* turn: strip padding from received channel data messages
	- this fixes an interop issue with Edge browser
	- thanks to Philipp Hancke for reporting the issue

## Version 0.4.11 - 2014-12-09 Alfred E. Heggestad <aeh@db.org>
* build: added support for static build (make STATIC=1)
* debian: minor improvements and updates
* filedb: new module implementing a file-based database for authentication credentials (in /etc/restund.auth)
* restauth: new module implementing REST-based authentication, as of draft-uberti-behave-turn-rest-00
* db: added restund_db_set_auth_handler()
* dtls: add support for DTLS-transport
* tcp: improved cleanup of idle TCP-connections

## Version 0.4.2 - 2012-09-09 Alfred E. Heggestad <aeh@db.org>
* added support for debian
* use thread-safe %m instead of strerror()
* tcp: setting send queue size limit: 8192
* turn: ensure request replies are not dropped due to full tcp send queue by limiting max queue size for relay data

## Version 0.4.1 - 2012-04-21 Alfred E. Heggestad <aeh@db.org>
* auth: improved nonce handling

## Version 0.4.0 - 2011-12-25 Alfred E. Heggestad <aeh@db.org>
* Version 0.4.0
* docs: add README
* tcp: add TCP length checks

## Version 0.3.0 - 2011-09-07 Alfred E. Heggestad <aeh@db.org>
* Version 0.3.0
* Added support for TCP and TLS transports
