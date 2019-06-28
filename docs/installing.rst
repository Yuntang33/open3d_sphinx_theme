
************
Installation
************

Via Python Package
==================

Install the package (or add it to your ``requirements.txt`` file):

.. code:: bash

    pip install open3d_sphinx_theme

In your ``conf.py`` file:

.. code:: python

    html_theme = "open3d_sphinx_theme"

Via Git or Download
===================

Symlink or subtree the ``open3d_sphinx_theme/open3d_sphinx_theme`` repository into your documentation at
``docs/_themes/open3d_sphinx_theme`` then add the following two settings to your Sphinx
``conf.py`` file:

.. code:: python

    html_theme = "open3d_sphinx_theme"
    html_theme_path = ["_themes", ]

