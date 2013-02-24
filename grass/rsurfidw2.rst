R.SURF.IDW2 - SURFACE GENERATION.
=================================

Description
-----------

Parameters
----------

- ``Input raster layer[Raster]``:
- ``Number of interpolation points[Number]``:
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

	sextante.runalg('grass:r.surf.idw2', input, npoints, grass_region_parameter, grass_region_cellsize_parameter, output)
