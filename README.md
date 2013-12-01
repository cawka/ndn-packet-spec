Relocation
==========

Spec has been moved to SVN.


Prerequisites
=============

To "compile" documentation into html form you would need to install Sphinx documentation package, which should be relatively trivial.

If you're on OSX platform:

- If you have macports, then

    sudo port install py27-sphinx
    sudo port selectsphinx py27-sphinx

    sudo easy_install-2.7 sphinxcontrib-fulltoc
    sudo easy_install-2.7 sphinxcontrib-bibtex

- Install from source: http://sphinx-doc.org/install.html

- Install from .pkg binary package: http://named-data.net/binaries/sphinx-doc-0.2.pkg

If you're on Ubuntu Linux:

    sudo apt-get install python-sphinx

    sudo easy_install sphinxcontrib-fulltoc
    sudo easy_install sphinxcontrib-bibtex

Compilation
===========

Just type

    make html

And a set of HTML pages will be build under ``_build/html``


You can also type

    make latexpdf

This way Sphinx will prepare .tex file and will try to build .pdf document.

