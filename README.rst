**********************************************
Django Simple Captcha with mongoengine support
**********************************************

.. image:: https://travis-ci.org/mbi/django-simple-captcha.png?branch=master

Django Simple Captcha is an extremely simple, yet highly customizable Django application to add captcha images to any Django form.
This Django Simple Captcha version works with mongoengine ODM as model backend.

.. image:: http://django-simple-captcha.googlecode.com/files/Captcha3.png

Features
++++++++

* Very simple to setup and deploy, yet very configurable
* Can use custom challenges (e.g. random chars, simple maths, dictionary word, ...)
* Custom generators, noise and filter functions alter the look of the generated image
* Supports text-to-speech audio output of the challenge text, for improved accessibility
* Ajax refresh

Requirements
++++++++++++

* Django 1.3+
* A recent version of the Python Imaging Library (PIL 1.1.7 or Pillow 2.0+) compiled with FreeType support
* Flite is required for text-to-speech (audio) output, but not mandatory
* mongoengine 0.7.9+

Python 3 compatibility
++++++++++++++++++++++

The current development version supports Python3 via the `six <https://pypi.python.org/pypi/six>`_ compatibility layer.
You will need to install `Pillow HEAD <https://github.com/python-imaging/Pillow>`_ because PIL doesn't support Python3 yet.

Note: This version has not been tested with Python3.

Documentation
+++++++++++++

Read the `documentation online <http://readthedocs.org/docs/django-simple-captcha>`_.
