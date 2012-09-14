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
using Firefox on port 80 using Http.

Notes
-----

Really use Firefox to connect to it.  Chromium
doesn't support some needed features, and looks
terrible.  Other browsers are untested.
