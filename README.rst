===================================
Awesome BlackScience.Tech |awesome|
===================================
.. See also `中文 <README-zh_CN.md>`_

Data
----

Land Cover
^^^^^^^^^^

- `Global Land Cover <http://www.fao.org/land-water/land/land-governance/land-resources-planning-toolbox/category/details/en/c/1036355/>`_
- `FROM-GLC10 <http://data.ess.tsinghua.edu.cn/fromglc10_2017v01.html>`_: |FROM-GLC|
- `FROM-GLC-2017 <http://data.ess.tsinghua.edu.cn/fromglc2017v1.html>`_
- `FROM-GLC-2015 <http://data.ess.tsinghua.edu.cn/fromglc2015_v1.html>`_
- `CropScape <https://nassgeodata.gmu.edu/CropScape/>`_: Cropland Data Layer

Governance Area
^^^^^^^^^^^^^^^

- China

  * `Alibaba Cloud DavaV Atlas <http://datav.aliyun.com/tools/atlas/>`_
- Global

Institutions and Projects
-------------------------

- `the Department of Earth System Science, Tsinghua University <http://data.ess.tsinghua.edu.cn/>`_
- `FAO <https://www.fao.org>`_

  * `GIEWS <http://www.fao.org/giews/en/>`_: Global Information and Early Warning System
- [EU Science Hub]

  * `MARS <https://ec.europa.eu/jrc/en/mars>`_: Monitoring Agricultuarl ResourceS

Learning Resources
------------------

- `Quantitative Plant`_: A website presenting image analysis software tools and models for plants

Models
------

Cotton2K
^^^^^^^^

Cotton2K is a cotton simulation model specially adapted for irrigated cotton production in arid regions. It was written by `Avishalom Marani <https://plantscience.agri.huji.ac.il/avishalom-marani>`_

======== ================ =========== ============== =============
  Name        Author       Language   Latest Version Latest Update
======== ================ =========== ============== =============
Cotton2K Avishalom Marani C++/Fortran      4.0           2004
======== ================ =========== ============== =============

Packages
--------

Input/Output
^^^^^^^^^^^^

- GDAL_: A translator library for raster and vector geospatial data formats that is released under an X/MIT style Open Source License by the Open Source Geospatial Foundation.
- |rio|_: Reads and writes geospatial raster data.

Satellite Specific
^^^^^^^^^^^^^^^^^^

- `Landsat-Util <https://pythonhosted.org/landsat-util>`_: A command line utility that makes it easy to search, download, and process Landsat imagery.
- `SentinelHub <https://sentinelhub-py.readthedocs.io/>`_: Allows users to make OGC (WMS and WCS) web requests to download and process satellite images within your Python scripts. It supports Sentinel-2 L1c and L2A, Sentinel-1, Landsat 8, MODIS and DEM data source.

Atmospheric Correction
^^^^^^^^^^^^^^^^^^^^^^

- `MULTIPLY - Sensor Invariant Atmospheric Correction (SIAC) <https://siac.readthedocs.io/>`_: This atmospheric correction method uses MODIS MCD43 BRDF product to get a coarse resolution simulation of earth surface.
- `Atmospheric and Radiometric Correction of Satellite Imagery (ARCSI) <https://www.arcsi.remotesensing.info/>`_: Provide as automatic as possible method of generating Analysis Ready Data (ARD).

Processing
^^^^^^^^^^

- `EarthPy <https://earthpy.readthedocs.io>`_

Crop Simulation
^^^^^^^^^^^^^^^

- |PCSE|_ - PCSE: A framework developed for implementing crop simulation models developed in Wageningen.

========= =========================================== ====================== ================ =================== ======================= ================= ================== ======================
Name      Version                                     Last Commit            Stars            Downloads           Lines of Code           License           Coverage           Contributors
========= =========================================== ====================== ================ =================== ======================= ================= ================== ======================
thermo_   |thermo version|_ |thermo conda version|_   |thermo last commit|_  |thermo stars|   |thermo downloads|  |thermo lines of code|  |thermo license|  |thermo coverage|  |thermo contributors|
MetPy_    |MetPy version|_ |MetPy conda version|_     |MetPy last commit|_   |MetPy stars|    |MetPy downloads|   |MetPy lines of code|   |MetPy license|   |MetPy coverage|   |MetPy contributors|
PCSE_     |PCSE version|_                             |PCSE last commit|_    |PCSE stars|     |PCSE downloads|    |PCSE lines of code|    |PCSE license|                       |PCSE contributors|
AstroPy_  |AstroPy version|_ |AstroPy conda version|_ |AstroPy last commit|_ |AstroPy stars|  |AstroPy downloads| |AstroPy lines of code| |AstroPy license| |AstroPy coverage| |AstroPy contributors|
========= =========================================== ====================== ================ =================== ======================= ================= ================== ======================

.. |awesome|                   image:: https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg
.. |FROM-GLC|                  image:: http://data.ess.tsinghua.edu.cn/title.png
.. _`Quantitative Plant`:              https://quantitative-plant.org
.. _GDAL:                              https://gdal.org
.. |rio|                     replace:: Rasterio
.. _rio:                               https://rasterio.readthedocs.io/
.. _thermo:                            https://thermo.readthedocs.io/
.. |thermo version|            image:: https://img.shields.io/pypi/v/thermo
.. _`thermo version`:                  https://pypi.org/project/thermo
.. |thermo conda version|      image:: https://img.shields.io/conda/vn/conda-forge/thermo
.. _`thermo conda version`:            https://anaconda.org/conda-forge/thermo
.. |thermo last commit|        image:: https://img.shields.io/github/last-commit/CalebBell/thermo?label
.. _`thermo last commit`:              https://github.com/CalebBell/thermo
.. |thermo stars|              image:: https://img.shields.io/github/stars/CalebBell/thermo?label
.. |thermo downloads|          image:: https://img.shields.io/pypi/dm/thermo?label=pypi
.. |thermo lines of code|      image:: https://img.shields.io/tokei/lines/github/CalebBell/thermo?label
.. |thermo license|            image:: https://img.shields.io/pypi/l/thermo?label
.. |thermo coverage|           image:: https://img.shields.io/coveralls/github/CalebBell/thermo?label
.. |thermo contributors|       image:: https://img.shields.io/github/contributors/CalebBell/thermo?label
.. _MetPy:                             https://github.com/Unidata/MetPy
.. |MetPy version|             image:: https://img.shields.io/pypi/v/MetPy
.. _`MetPy version`:                   https://pypi.org/project/MetPy
.. |MetPy conda version|       image:: https://img.shields.io/conda/vn/conda-forge/MetPy
.. _`MetPy conda version`:             https://anaconda.org/conda-forge/metpy
.. |MetPy last commit|         image:: https://img.shields.io/github/last-commit/Unidata/MetPy?label
.. _`MetPy last commit`:               https://github.com/Unidata/MetPy
.. |MetPy stars|               image:: https://img.shields.io/github/stars/Unidata/MetPy?label
.. |MetPy downloads|           image:: https://img.shields.io/pypi/dm/metpy?label=pypi
.. |MetPy lines of code|       image:: https://img.shields.io/tokei/lines/github/Unidata/MetPy?label
.. |MetPy license|             image:: https://img.shields.io/pypi/l/metpy?label
.. |MetPy coverage|            image:: https://img.shields.io/codecov/c/github/Unidata/MetPy?label
.. |MetPy contributors|        image:: https://img.shields.io/github/contributors/Unidata/MetPy?label
.. |PCSE|                    replace:: Python Crop Simulation Environment
.. _PCSE:                              https://pcse.readthedocs.io
.. |PCSE version|              image:: https://img.shields.io/pypi/v/PCSE
.. _`PCSE version`:                    https://pypi.org/project/PCSE
.. |PCSE last commit|          image:: https://img.shields.io/github/last-commit/ajwdewit/pcse?label
.. _`PCSE last commit`:                https://github.com/ajwdewit/pcse
.. |PCSE stars|                image:: https://img.shields.io/github/stars/ajwdewit/pcse?label
.. |PCSE downloads|            image:: https://img.shields.io/pypi/dm/pcse?label=pypi
.. |PCSE lines of code|        image:: https://img.shields.io/tokei/lines/github/ajwdewit/pcse?label
.. |PCSE license|              image:: https://img.shields.io/pypi/l/pcse?label
.. |PCSE contributors|         image:: https://img.shields.io/github/contributors/ajwdewit/pcse?label
.. _AstroPy:                           https://www.astropy.org
.. |AstroPy version|           image:: https://img.shields.io/pypi/v/astropy
.. _`AstroPy version`:                 https://pypi.org/project/astropy
.. |AstroPy conda version|     image:: https://img.shields.io/conda/v/main/astropy?label=conda
.. _`AstroPy conda version`:           https://anaconda.org/anaconda/astropy
.. |AstroPy last commit|       image:: https://img.shields.io/github/last-commit/astropy/astropy?label
.. _`AstroPy last commit`:             https://github.com/astropy/astropy
.. |AstroPy stars|             image:: https://img.shields.io/github/stars/astropy/astropy?label
.. |AstroPy downloads|         image:: https://img.shields.io/pypi/dm/astropy?label=pypi
.. |AstroPy lines of code|     image:: https://img.shields.io/tokei/lines/github/astropy/astropy?label
.. |AstroPy license|           image:: https://img.shields.io/pypi/l/astropy?label
.. |AstroPy coverage|          image:: https://img.shields.io/codecov/c/github/astropy/astropy?label
.. |AstroPy contributors|      image:: https://img.shields.io/github/contributors/astropy/astropy?label
