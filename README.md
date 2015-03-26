Novena Heirloom Support
=======================

The Heirloom laptop adds some minor extra hardware, such as an internal
fan.  This package supports this additional hardware.

Building
------------

To build the package, run "git-buildpackage [tag]" where [tag] is a valid upstream tag,
such as v1.0.  You might also need to add -uc -us if building an unsigned package.  E.g.:

    git-buildpackage -us -uc --git-upstream-tag=v1.0


Installation
------------

To install, simply use dpkg to install the resulting .deb package.
