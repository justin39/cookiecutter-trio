Todo:

* add a test that we can run cookiecutter, install, run tests, run
  towncrier, docs work (maybe run the travis script?)
* switch to pytest-trio


cookiecutter-trio
=================

This is a cookiecutter template for Python projects that use `Trio
<https://trio.readthedocs.io>`__. It makes it easy to start a new
project, by providing a bunch of preconfigured boilerplate for:

* pytest with trio integration
* sphinx docs with sphinxcontrib-trio enabled
* Readthedocs to publish your docs
* Travis and Appveyor to test your package on all the different
  platforms Trio supports: Windows + MacOS + Linux, CPython + PyPy
* Codecov to track code coverage information
* towncrier for easy release note management
* black so you don't have to think about formatting

This is just an optional starting point – you don't have to use it,
and if you do use it, then all it does is generate a bunch of
boilerplate, so once it's done you're free to customize everything to
your liking. But, this is the same basic setup used to develop Trio
itself and many related projects, so the closer you stick to the
template the easier it will be for new contributors to hit the ground
running.


Let's do this!
--------------

1. ``pip install -U cookiecutter`` (or check out the `detailed
   cookiecutter install instructions
   <https://cookiecutter.readthedocs.io/en/latest/installation.html>`__)
2. ``cookiecutter gh:python-trio/cookiecutter-trio``
3. Answer the questions. This will create a directory named after your
   project (e.g., if you said your project is called
   ``superwhizbang``, then there will be a directory called
   ``superwhizbang/``).
4. Look through ``{your project}/CHEATSHEET.rst`` for a
   checklist of things to think about and tips on how to do basic
   things like running tests.


License
-------

This cookiecutter template is released under the CC0 Public Domain
Dedication – see the file LICENSE for details. Basically what this
means is that you can use it for any kind of project you want under
whatever license terms you want, and you don't even have to worry
about giving us credit or anything like that.
