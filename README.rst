.. image:: https://travis-ci.org/PyBossa/pybossa.png
   :target: https://travis-ci.org/#!/PyBossa/pybossa

PyBossa is an open source platform for crowd-sourcing online (volunteer)
assistance to perform tasks that require human cognition, knowledge or
intelligence (e.g. image classification, transcription, information location
etc). 

PyBossa was inspired by the BOSSA_ crowdsourcing engine but is written in
python (hence the name!). It can be used for any distributed tasks application
but was initially developed to help scientists and other researchers
crowd-source human problem-solving skills!

.. _BOSSA: http://bossa.berkeley.edu/


See it in Action
================

PyBossa powers http://pybossa.com/ - check it out!


Installing and Upgrading
========================

See doc/install.rst or http://pybossa.readthedocs.org/en/latest/install.html

Running Tests
=============

Set SQLALCHEMY_DATABASE_TEST_URI e.g.::

  SQLALCHEMY_DATABASE_URI = 'postgres://pybossa:pass@localhost/pybossa'

Then run the tests (requires nose)::

  nosetests -v test/


Useful Links
============

* Documentation: http://pybossa.readthedocs.org/
* Mailing List http://lists.okfn.org/mailman/listinfo/open-science-dev


Authors
=======

* Daniel Lombraña González - Citizen Cyberscience Centre
* Rufus Pollock - Open Knowledge Foundation
* Chris Powell - EPICollect
* David Anderson - BOINC / Berkeley (via BOSSA)

* Twitter Bootstrap Icons by Glyphicons http://http://glyphicons.com/
* FontAwesome fonts by http://fortawesome.github.com/Font-Awesome/


