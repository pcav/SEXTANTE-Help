R.BILINEAR - BILINEAR INTERPOLATION UTILITY FOR RASTER MAP LAYERS.
==================================================================

Description
-----------

Parameters
----------

- ``Input raster layer[Raster]``:
- ``Specific input value to be assigned to the north and/or south poles for longitude-latitude grids[Number]``:
- ``Specific input value to be assigned to the north and/or south poles for longitude-latitude grids[Number]``:
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

	sextante.runalg('grass:r.bilinear', input, north, east, grass_region_parameter, grass_region_cellsize_parameter, output)
