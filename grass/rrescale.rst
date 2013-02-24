R.RESCALE - RESCALES THE RANGE OF CATEGORY VALUES IN A RASTER LAYER.
====================================================================

Description
-----------

Parameters
----------

- ``Input raster layer[Raster]``:
- ``The input data range to be rescaled[Range]``:
- ``The output data range[Range]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Output raster layer[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.rescale', input, from, to, grass_region_parameter, grass_region_cellsize_parameter, output)
