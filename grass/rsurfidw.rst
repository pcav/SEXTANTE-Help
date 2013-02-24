R.SURF.IDW - SURFACE INTERPOLATION UTILITY FOR RASTER LAYERS.
=============================================================

Description
-----------

Parameters
----------

- ``Name of input raster layer[Raster]``:
- ``Number of interpolation points[Number]``:
- ``Output is the interpolation error[Boolean]``:
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

	sextante.runalg('grass:r.surf.idw', input, npoints, -e, grass_region_parameter, grass_region_cellsize_parameter, output)
