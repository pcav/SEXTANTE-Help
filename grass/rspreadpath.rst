R.SPREADPATH - RECURSIVELY TRACES THE LEAST COST PATH BACKWARDS TO CELLS FROM WHICH THE CUMULATIVE COST WAS DETERMINED.
=======================================================================================================================

Description
-----------

Parameters
----------

- ``x_input[Raster]``:
- ``y_input[Raster]``:
- ``coordinate[String]``:
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

	sextante.runalg('grass:r.spreadpath', x_input, y_input, coordinate, grass_region_parameter, grass_region_cellsize_parameter, output)
