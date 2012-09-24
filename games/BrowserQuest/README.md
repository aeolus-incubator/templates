BrowserQuest
============

This Aeolus template starts a BrowserQuest v1.2 server.


Known to work on
----------------

* EC2 (64-bit instances, including m1.small)
* VMware vSphere (64-bit instances)


Requirements
------------

Tcp port 80 must be open for incoming traffic.


How to use
----------

Build and launch the instance, then connect to it on port 80 using http.


Browser support
---------------

* Firefox (any recent) - Works well.
* Safari 6.x - Works well.
* Chrome - Sounds effects don't work.
* Chromium - Varies wildly. Some releases display using BrowserQuest's "mobile" layout, with very small screen. Not recommended.
* Opera - Doesn't work, no WebSocket support.
* IE (any version) - Untested.
