R.SURF.CONTOUR - SURFACE GENERATION PROGRAM FROM RASTERIZED CONTOURS.
=====================================================================

Description
-----------

Parameters
----------

- ``Raster layer with rasterized contours[Raster]``:
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

	sextante.runalg('grass:r.surf.contour', input, grass_region_parameter, grass_region_cellsize_parameter, output)
