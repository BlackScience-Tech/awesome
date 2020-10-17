# Awesome BlackScience.Tech [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/BlackScience-Tech/awesome)

See also [中文](README-zh_CN.md)

## Data

### Land Cover
- [Global Land Cover](http://www.fao.org/land-water/land/land-governance/land-resources-planning-toolbox/category/details/en/c/1036355/)
- [FROM-GLC10](http://data.ess.tsinghua.edu.cn/fromglc10_2017v01.html): ![Finer Resolution Observation and Monitoring-Global Land Cover](http://data.ess.tsinghua.edu.cn/title.png)
- [FROM-GLC-2017](http://data.ess.tsinghua.edu.cn/fromglc2017v1.html)
- [FROM-GLC-2015](http://data.ess.tsinghua.edu.cn/fromglc2015_v1.html)
- [CropScape](https://nassgeodata.gmu.edu/CropScape/): Cropland Data Layer

### Governence area
- China
  * [Alibaba Cloud DataV Atlas](http://datav.aliyun.com/tools/atlas/)
- Global

## Institutions and Projects
- [the Department of Earth System Science, Tsinghua University](http://data.ess.tsinghua.edu.cn/)
- [FAO](https://www.fao.org/)
  * [GIEWS](http://www.fao.org/giews/en/): Global Information and Early Warning System
- [EU Science Hub]
  * [MARS](https://ec.europa.eu/jrc/en/mars): Monitoring Agricultural ResourceS

## Learning Resources
- [Quantitative Plant](https://quantitative-plant.org): A website presenting image analysis software tools and models for plants

## Model

### Cotton2k
Cotton2K is a cotton simulation model specially adapted for irrigated cotton production in arid regions. It was written by [Avishalom Marani](https://plantscience.agri.huji.ac.il/avishalom-marani) 

| Name     |      Author      |  Language   | Latest Version | Latest Update |
|:---------|:----------------:|:-----------:|:--------------:|:-------------:|
| Cotton2K | Avishalom Marani | C++/Fortran |      4.0       |     2004      |

## Packages

### Input/Output
- [GDAL](https://gdal.org): You know who
- [Rasterio](https://rasterio.readthedocs.io/): Reads and writes geospatial raster data.

### Satellite Specific
- [Landsat-Util](https://pythonhosted.org/landsat-util/): A command line utility that makes it easy to search, download, and process Landsat imagery.
- [SentinelHub](http://sentinelhub-py.readthedocs.io/): Allows users to make OGC (WMS and WCS) web requests to download and process satellite images within your Python scripts. It supports Sentinel-2 L1C and L2A, Sentinel-1, Landsat 8, MODIS and DEM data source.

### Atmospheric Correction
- [MULTIPLY - Sensor Invariant Atmospheric Correction (SIAC)](https://siac.readthedocs.io/): This atmospheric correction method uses MODIS MCD43 BRDF product to get a coarse resolution simulation of earth surface.
- [Atmospheric and Radiometric Correction of Satellite Imagery (ARCSI)](https://www.arcsi.remotesensing.info/): Provide as automatic as possible method of generating Analysis Ready Data (ARD).

### Processing
- [EarthPy](https://earthpy.readthedocs.io/)

### Crop Simulation
- [Python Crop Simulation Environment - PCSE](https://pcse.readthedocs.io/): A framework developed for implementing crop simulation models developed in Wageningen.


|     Name     |      Version    |Last Commit| Stars  |    Downloads    |Lines of Code|License |Coverage|Contributors|
|:------------:|:---------------:|:---------:|:------:|:---------------:|:-----------:|:------:|:------:|-----------:|
|[thermo][01]  |![][01v]![][01vc]|![][01a]   |![][01s]|![][01d]![][01dc]|![][01z]     |![][01l]|![][01c]|![][01t]    |
|[MetPy][02]   |![][02v]![][02vc]|![][02a]   |![][02s]|![][02d]![][02dc]|![][02z]     |![][02l]|![][02c]|![][02t]    |
|[Cotton2K][03]|                 |![][03a]   |![][03s]|                 |![][03z]     |![][03l]|![][03c]|![][03t]    |
|[PCSE][04]    |![][04v]         |![][04a]   |![][04s]|![][04d]         |![][04z]     |![][04l]|        |![][04t]    |
|[AstroPy][05] |![][05v]![][05vc]|![][05a]   |![][05s]|![][05d]![][05dc]|![][05z]     |![][05l]|![][05c]|![][05t]

[01]: https://github.com/CalebBell/thermo
[01v]: https://img.shields.io/pypi/v/thermo
[01vc]: https://img.shields.io/conda/vn/conda-forge/thermo
[01a]: https://img.shields.io/github/last-commit/CalebBell/thermo
[01s]: https://img.shields.io/github/stars/CalebBell/thermo
[01d]: https://img.shields.io/pypi/dd/thermo
[01dc]: https://img.shields.io/conda/dn/conda-forge/thermo
[01z]: https://img.shields.io/tokei/lines/github/CalebBell/thermo
[01l]: https://img.shields.io/github/license/CalebBell/thermo
[01c]: https://img.shields.io/coveralls/github/CalebBell/thermo
[01t]: https://img.shields.io/github/contributors/CalebBell/thermo
[02]: https://github.com/Unidata/MetPy
[02v]: https://img.shields.io/pypi/v/MetPy
[02vc]: https://img.shields.io/conda/vn/conda-forge/MetPy
[02a]: https://img.shields.io/github/last-commit/Unidata/MetPy
[02s]: https://img.shields.io/github/stars/Unidata/MetPy
[02d]: https://img.shields.io/pypi/dd/MetPy
[02dc]: https://img.shields.io/conda/dn/conda-forge/MetPy
[02z]: https://img.shields.io/tokei/lines/github/Unidata/MetPy
[02l]: https://img.shields.io/github/license/Unidata/MetPy
[02c]: https://img.shields.io/codecov/c/github/Unidata/MetPy
[02t]: https://img.shields.io/github/contributors/Unidata/MetPy
[03]: https://github.com/tcztzy/cotton2k
[03a]: https://img.shields.io/github/last-commit/tcztzy/cotton2k
[03s]: https://img.shields.io/github/stars/tcztzy/cotton2k
[03c]: https://img.shields.io/codecov/github/tcztzy/cotton2k
[03z]: https://img.shields.io/tokei/lines/github/tcztzy/cotton2k
[03l]: https://img.shields.io/github/license/tcztzy/cotton2k
[03c]: https://img.shields.io/codecov/c/github/tcztzy/cotton2k
[03t]: https://img.shields.io/github/contributors/tcztzy/cotton2k

[04]: https://github.com/ajwdewit/pcse
[04v]: https://img.shields.io/pypi/v/pcse
[04a]: https://img.shields.io/github/last-commit/ajwdewit/pcse
[04s]: https://img.shields.io/github/stars/ajwdewit/pcse
[04d]: https://img.shields.io/pypi/dd/pcse
[04z]: https://img.shields.io/tokei/lines/github/ajwdewit/pcse
[04l]: https://img.shields.io/pypi/l/pcse
[04t]: https://img.shields.io/github/contributors/ajwdewit/pcse

[05]: https://www.astropy.org/
[05v]: https://img.shields.io/pypi/v/astropy
[05vc]: https://img.shields.io/conda/v/main/astropy
[05a]: https://img.shields.io/github/last-commit/astropy/astropy
[05s]: https://img.shields.io/github/stars/astropy/astropy
[05d]: https://img.shields.io/pypi/dd/astropy
[05dc]: https://img.shields.io/conda/dn/main/astropy
[05z]: https://img.shields.io/tokei/lines/github/astropy/astropy
[05l]: https://img.shields.io/github/license/astropy/astropy
[05c]: https://img.shields.io/codecov/c/github/astropy/astropy
[05t]: https://img.shields.io/github/contributors/astropy/astropy