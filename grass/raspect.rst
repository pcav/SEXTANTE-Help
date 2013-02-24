R.ASPECT - GENERATES RASTER MAPS OF ASPECT FROM A ELEVATION RASTER MAP.
=======================================================================

Description
-----------

Parameters
----------

- ``Elevation[Raster]``:
- ``Data type[Selection]``:
- ``Multiplicative factor to convert elevation units to meters[Number]``:
- ``Minimum slope val. (in percent) for which aspect is computed[Number]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Output aspect layer[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.aspect', elevation, prec, zfactor, min_slp_allowed, grass_region_parameter, grass_region_cellsize_parameter, aspect)

	Available options for selection parameters:

	prec(Data type)
		0 - float
		1 - double
		2 - int
