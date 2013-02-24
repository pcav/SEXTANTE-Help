R.COMPOSITE - COMBINES RED, GREEN AND BLUE RASTER MAPS INTO A SINGLE COMPOSITE RASTER MAP.
==========================================================================================

Description
-----------

Parameters
----------

- ``Red[Raster]``:
- ``Green[Raster]``:
- ``Blue[Raster]``:
- ``Number of levels to be used for each component[Number]``:
- ``Dither[Boolean]``:
- ``Use closest color[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Output RGB image[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.composite', red, green, blue, levels, -d, -c, grass_region_parameter, grass_region_cellsize_parameter, output)
