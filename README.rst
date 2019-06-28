Open3D Sphinx Theme
*******************

The ``open3d_sphinx_theme`` is a sphinx_ theme based on
`Read the Docs Sphinx Theme <https://github.com/readthedocs/sphinx_rtd_theme>`__.

Usage 1: Installing
===================

.. code:: bash

    python setup.py install


In ``conf.py``

.. code:: python

    import open3d_sphinx_theme

    html_theme = "open3d_sphinx_theme"
    html_theme_path = [open3d_sphinx_theme.get_html_theme_path()]


Usage 2: Use as submodule
=========================

Set the correct path

.. code:: python

    theme_path = os.path.join(current_file_dir, "..", "3rdparty", "open3d_sphinx_theme")
    static_path = os.path.join(theme_path, "static")

    html_theme = "open3d_sphinx_theme"
    html_theme_path = [theme_path]
    html_favicon = "_static/open3d_logo.ico"
    html_static_path = [static_path]
