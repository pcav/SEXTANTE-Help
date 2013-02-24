I.ATCORR - PERFORMS ATMOSPHERIC CORRECTION USING THE 6S ALGORITHM.
==================================================================

Description
-----------

Parameters
----------

- ``Name of input raster map[Raster]``:
- ``Input from ETM+ image taken after July 1, 2000[Boolean]``:
- ``Input from ETM+ image taken before July 1, 2000[Boolean]``:
- ``Input altitude raster map in m (optional)[Raster]``:
- ``Input visibility raster map in km (optional)[Raster]``:
- ``Name of input text file[File]``:
- ``Input imagery range [0,255][Range]``:
- ``Try to increase computation speed when altitude and/or visibility map is used[Boolean]``:
- ``Output raster is floating point[Boolean]``:
- ``Rescale output raster map [0,255][Range]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Name for output raster map[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:i.atcorr', iimg, -a, -b, ialt, ivis, icnd, iscl, -o, -f, oscl, grass_region_parameter, grass_region_cellsize_parameter, oimg)
