Getting Started
===============

This page details how to get started with molecool.

Installation
------------
To install molecool, set up a conda environment with the following dependencies:

* numpy
* matplotlib

To do a development install use::

  pip install -e .

Usage
-----
Once installed, you can use the package::

  import molecool

  benzene_symbols,benzene_coords = molecool.open_xyz('benzene.xyz')

Examples of Code Blocks
++++++++++++++++++++++++

.. code-block:: python

  import numpy as np


