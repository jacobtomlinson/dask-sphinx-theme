Welcome to Dask Sphinx Theme's documentation!
=============================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:

This is the official Sphinx theme for Dask documentation.  It extends the
``sphinx_rtd_theme`` project, but adds custom styling and a navigation bar to
additional Dask subprojects.

When creating a Dask subproject you can include this theme by changing this
line in your conf.py file

.. code-block:: python

   html_theme = 'dask_sphinx_theme'

And by including ``dask_sphinx_theme`` as a requirement in your documentation
installation.