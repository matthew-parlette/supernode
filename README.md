supernode
=========

An n2n supernode start script

Description
===========

This script is usable by upstart (tested in Ubuntu), but works by simply starting the supernode program in the background, and stopping it by using killall.

Installation
============

Save the script under /etc/init.d/supernode. Modify the file to set the username that the program should run as, as well as the log file (which is just the output of the program to stdout).

Once this is done, you can run:
$ update-rc.d supernode defaults

In order to have this service start with the system.
