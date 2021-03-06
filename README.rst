PyconUK website
===============

.. image:: https://travis-ci.org/PyconUK/pyconuk.github.io.svg?branch=master
       :target: https://travis-ci.org/PyconUK/pyconuk.github.io

This is the website for PyconUK. It is hosted via GitHub Pages and available via http://pyconuk.org/.

We welcome pull requests for improvements! (Please see CONTRIBUTING.rst for details.)

Use the following process to submit changes:

* Fork the repository.
* Create a descriptive branch name for the change you are proposing.
* Push your changes in your local branch back to your remote GitHub repository.
* In GitHub, create a pull request from your branch against our upstream repository.
* Someone (not you) will check the change and either merge it (thus automatically updating the website) or add comments for further changes or a reason for rejection.

If you're not a coder please feel free to create issues here: https://github.com/PyconUK/pyconuk.github.io/issues

That's it!

:-)

Usage
-----

This site uses Jekyll_. The official docs are good, but here's a quickstart:

* Ensure you have rvm_ or rbenv_
* Ensure you have bundler_ - if you can't ``bundle`` on the command line, ``gem install bundler``
* ``bundle install`` in the git repo to fetch the dependencies
* ``bundle exec jekyll serve -w`` will run a development server listening on port 4000
* ``bundle exec jekyll build`` will build the site in ``$gitroot/_site/``

Pages are essentially `Liquid templates`_. Essentially stick some YAML front-matter at the start containing page metadata (like `layout` and `title`) at the top of a Markdown / HTML file of content.

Travis will test branches, and branches won't get merged without review and passing tests, so dive right in!

.. _Jekyll: http://jekyllrb.com/
.. _rvm: https://rvm.io/
.. _rbenv: http://rbenv.org/
.. _bundler: http://bundler.io/
.. _Liquid templates: http://jekyllrb.com/docs/templates/
