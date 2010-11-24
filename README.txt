Introduction
============

Cufón aims to become a worthy alternative to sIFR, which despite its merits
still remains painfully tricky to set up and use. To achieve this ambitious goal
the following requirements were set:

* No plug-ins required – it can only use features natively supported by the client
* Compatibility – it has to work on every major browser on the market
* Ease of use – no or near-zero configuration needed for standard use cases
* Speed – it has to be fast, even for sufficiently large amounts of text

And now, after nearly a year of planning and research we believe that these
requirements have been met.

Source: https://github.com/sorccu/cufon/

How to use
==========

The official how to use is here: https://github.com/sorccu/cufon/wiki/Usage

You can jump to step 2 because of this add-on.


How to update this package
==========================

wget https://github.com/sorccu/cufon/blob/XXX/js/cufon.js
mv cufon.js cufon-XXX.js
update zcml
update default profile
add / update upgrade step

ROADMAP
=======

For this add-on just maintain the javascript, but for cufon:

* create a python generator
* integrate the generator inside Plone
