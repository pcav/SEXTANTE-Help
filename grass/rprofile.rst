R.PROFILE - OUTPUTS THE RASTER LAYER VALUES LYING ON USER-DEFINED LINE(S).
==========================================================================

Description
-----------

Parameters
----------

- ``Input raster layer[Raster]``:
- ``Profile coordinate pairs[String]``:
- ``Resolution along profile[Number]``:
- ``Character to represent no data cell[String]``:
- ``Output easting and northing in first two columns of four column output[Boolean]``:
- ``Output RRR:GGG:BBB color values for each profile point[Boolean]``:
- ``GRASS region extent[Extent]``:

Outputs
-------

- ``Output filename[File]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.profile', input, profile, res, null, -g, -c, grass_region_parameter, output)
