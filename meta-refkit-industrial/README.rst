This README file contains information on the contents of the
refkit-industrial layer.


Dependencies
============

This layer depends on::

   URI: git://git.openembedded.org/bitbake
   branch: master

   URI: git://git.openembedded.org/openembedded-core
   layers: meta
   branch: master

   URI: https://github.com/intel/intel-iot-refkit
   layers: refkit-core
   branch: master

   URI: http://git.openembedded.org/meta-openembedded
   layers: openembedded-layer, meta-python
   branch: master

   URI: https://github.com/bmwcarit/meta-ros.git
   layers: ros-layer
   branch: master

Patches
=======

See the "Submitting Patches" section in the top-level ``README.rst``.


Adding the refkit-industrial layer to your build
====================================================

See the "Layer Overview and Reuse" section in ``doc/introduction.rst``
for details.
