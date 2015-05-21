Multipkg
==============
Multipkg automates and versions your package builds.

Installation
--------------

Step 1. Change into multipkg source directory and run build.sh

Step 2. Install the newly created rpm/deb pacakge within the directory.


Usage
-----

Please refer to doc/multipkg-by-examples.md

build problem
-----
Build failed: error: bad date in %changelog: 四 5月 21 2015 09:11:29 user@centos 
you should change the lang first

    $ LANG=en_US.UTF-8
