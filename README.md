supernode
=========

An n2n supernode start script

Description
===========

This script is usable by upstart (tested in Ubuntu)

Installation
============

Save the script under /etc/init/supernode.conf.

Modify the file to set the username that the program should run as, as well as the logfile and port.

Once this is done, you can run:
$ sudo start supernode
