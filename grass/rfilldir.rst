R.FILL.DIR - FILTERS AND GENERATES A DEPRESSIONLESS ELEVATION LAYER AND A FLOW DIRECTION LAYER FROM A GIVEN ELEVATION RASTER LAYER.
===================================================================================================================================

Description
-----------

Parameters
----------

- ``Elevation[Raster]``:
- ``Output aspect direction format[Selection]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Depressionless DEM[Raster]``:
- ``Flow direction[Raster]``:
- ``Problem areas[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.fill.dir', input, type, grass_region_parameter, grass_region_cellsize_parameter, elevation, direction, areas)

	Available options for selection parameters:

	type(Output aspect direction format)
		0 - grass
		1 - agnps
		2 - answers
