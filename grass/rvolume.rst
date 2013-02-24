R.VOLUME - CALCULATES THE VOLUME OF DATA "CLUMPS".
==================================================

Description
-----------

Parameters
----------

- ``Layer representing data that will be summed within clumps[Raster]``:
- ``Clumps layer (preferably the output of r.clump)[Raster]``:
- ``Generate unformatted report[Boolean]``:
- ``GRASS region extent[Extent]``:

Outputs
-------

- ``Vector points map to contain clump centroids[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.volume', data, clump, -f, grass_region_parameter, centroids)
