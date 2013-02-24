R.MAPCALCULATOR - CALCULATE NEW RASTER MAP FROM A R.MAPCALC EXPRESSION.
=======================================================================

Description
-----------

Parameters
----------

- ``Raster layer A[Raster]``:
- ``Raster layer B[Raster]``:
- ``Raster layer C[Raster]``:
- ``Raster layer D[Raster]``:
- ``Raster layer E[Raster]``:
- ``Raster layer F[Raster]``:
- ``Formula[String]``:
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

	sextante.runalg('grass:r.mapcalculator', amap, bmap, cmap, dmap, emap, fmap, formula, grass_region_parameter, grass_region_cellsize_parameter, outfile)
