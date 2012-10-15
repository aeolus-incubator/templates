Fedora Infrastructure
=====================

These templates are meant to facilitate the building of images
containing key components of Fedora Infrastructure with the cloud.

The components as as follows:

* mock - http://fedoraproject.org/wiki/Projects/Mock
  builds packages in clean / chrooted environments

* koji - https://fedoraproject.org/wiki/Koji
  hosted mock architecture consisting of a centralized
  hub server and build nodes that run mock on different
  architectures

* bodhi - http://fedoraproject.org/wiki/Bodhi
  facilitates fedora package update process


Known to work on
----------------

These templates build Fedora images with standard packages from the
Fedora repos so these should be able to be built for any cloud provider
which imagefactory has support for (oVirt, Openstack, EC2, etc).

All providers / scenarios haven't been tested so if you find a problem,
file an issue with the details and I'll look into it.


Requirements
------------

* mock does not have any external requirements

* the koji hub and build server, and bodhi run behind apache httpd, so 
  ports 80 and 443 need to be open on your instance

How to use
----------

Build the image and launch the instance, the services will be running
on your cloud provider which you can connect to using deltacloud, the
native tooling or any other mechanism.

Koji and bodhi will be available on port 80/443 of your instance.
