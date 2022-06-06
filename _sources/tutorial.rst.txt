Tutorial
========

This tutorial walks through the basics of creating a Github Pages site for a Python package. It focuses on `sphinx <https://www.sphinx-doc.org/en/master/>`_.

The tutorial will show off the Python package ``mycybergis`` in `cybergis/github-pages-demo <https://github.com/cybergis/github-pages-demo>`_ and an example notebook using the package.

.. note::
   
   **Before you start,** please setup a Github account, an environment with Git and `Sphinx installed <https://www.sphinx-doc.org/en/master/usage/installation.html>`_ and have some kind of Python package management software. I recommend `venv <https://docs.python.org/3/library/venv.html>`_ or `conda <https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html>`_. The tutorial assumes you have Sphinx installed and some way to install Python packages.

.. toctree::
    :maxdepth: 2
    :numbered:
    :caption: Tutorial Contents:

    tutorial/sphinx-quickstart.md
    tutorial/basic-rst
    tutorial/autodocs
    tutorial/nbsphinx
    tutorial/github-pages
    tutorial/advanced-topics