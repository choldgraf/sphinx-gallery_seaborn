Seaborn-style Sphinx-Gallery with Seaborn
=========================================

This repository demonstrates how to achieve a gallery of example images
that mimics the design used in the `seaborn documentation <seaborn.pydata.org>`_.
It uses ``sphinx-gallery`` to build the gallery, and a single custom CSS
file to style the gallery to look like seaborn.

For a demo, see the links below:

.. toctree::
   :maxdepth: 1

   default
   seaborn
   
   
For the CSS used to to generate this gallery, see
`this file in the repository <PATH TO CSS FILE>`_. You can use
this CSS in your own sphinx-gallery by adding it to your ``_static``
folder and configuring Sphinx to use it.

.. toctree::
   :hidden:
   
   auto_examples/index