***********
DECam Tools
***********

.. image:: http://img.shields.io/badge/powered%20by-AstroPy-orange.svg?style=flat
    :target: http://www.astropy.org
    :alt: Powered by Astropy Badge

********
Overview
********

DECam Tools was a python package designed to aid observers in processing and analyzing their
DECam images that have already been processed by the Community Pipeline. Most of the scripts
work with the InstCal files although users can really use files generated at any stage in the
Community pipeline including raw images, resampled images, and stacks.

I have since created the astropyp_ package, which includes functions for running AstrOmatic software like SExtractor, advanced photometry tools for calibrating images, and functions specific to specific instruments, like DECam. So all future updates for my DECam analysis will be in astropyp_ and decam-tools will no longer be maintained.


Acknowledgement
===============

I am not affiliated with the Dark Energy Survey, the Dark Energy Camera, CTIO, or NOAO, 
but I am a graduate student in astronomy who has been reducing my own DECam images and
thought that many of the tools I developed would be useful. Please acknowledge the use
of this code if you use it in your research.

Status reports for developers
-----------------------------

.. image:: https://travis-ci.org/fred3m/decam-tools.png?branch=master
    :target: https://travis-ci.org/fred3m/decam-tools
    :alt: Test Status

.. image:: https://coveralls.io/repos/fred3m/decam-tools/badge.svg?branch=master&service=github 
    :target: https://coveralls.io/github/fred3m/decam-tools?branch=master

.. _astropyp: https://github.com/fred3m/astropyp
