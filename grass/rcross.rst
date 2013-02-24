R.CROSS - CREATES A CROSS PRODUCT OF THE CATEGORY VALUES FROM MULTIPLE RASTER MAP LAYERS.
=========================================================================================

Description
-----------

Parameters
----------

- ``Input raster layers[MultipleInput]``:
- ``Non-zero data only[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Output layer[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.cross', input, -z, grass_region_parameter, grass_region_cellsize_parameter, output)
