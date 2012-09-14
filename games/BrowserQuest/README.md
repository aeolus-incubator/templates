BrowserQuest
============

This Aeolus template starts a BrowserQuest server,
pulling down the latest BrowserQuest git master head
when it's built.

Known to work on
----------------

* EC2 (64-bit instances, including m1.small)
* VMware vSphere (64-bit instances)

Requirements
------------

Tcp ports 80 and 8000 must be open for incoming
traffic.

How to use
----------

Build and launch the instance, then connect to it
on port 80 using http.

Browser support
---------------

* Firefox - Works well
* Safari - Works well
* Chrome - Sounds effects don't work
* Chromium - Plays in "mobile" mode only, very small screen
* Opera - Doesn't work, no WebSocket support
* IE (any version) - Untested

