=============================
dinosar-pangeo-demo
=============================

This repository contains a poster from AGU 2018 as well as some examples.

We've created a set of Sentinel-1 Interferograms covering the Rattlesnake Ridge Landslide outside of Union Gap Washington using the dinoSAR_ python package. By storing the data on AWS as Cloud-Optimized Geotiffs (COG_) with STAC_ metadata, we can use the STAC-browser_  utility to visualize and share this dataset:

https://dinosar-agu.netlify.com


For quantitative interactive analysis of this dataset, the Pangeo project has created excellent utilities to easily work with scalable resources on the Cloud. An example interactive Jupyter notebook can be launched with the button below:

|Binder|

See http://pangeo.io for more information!

.. |Binder| image:: http://binder.pangeo.io/badge.svg
    :target: http://binder.pangeo.io/v2/gh/scottyhq/agu2018/master?urlpath=lab/tree/notebooks/0-dinosar-demo.ipynb

.. _dinoSAR: https://github.com/scottyhq/dinosar
.. _COG: https://www.cogeo.org
.. _STAC: https://github.com/radiantearth/stac-spec
.. _STAC-browser: https://github.com/radiantearth/stac-browser
