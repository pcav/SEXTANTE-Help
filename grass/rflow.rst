R.FLOW - CONSTRUCTION OF SLOPE CURVES (FLOWLINES), FLOWPATH LENGTHS, AND FLOWLINE DENSITIES (UPSLOPE AREAS) FROM A RASTER DIGITAL ELEVATION MODEL (DEM).
========================================================================================================================================================

Description
-----------

Parameters
----------

- ``Elevation[Raster]``:
- ``Aspect[Raster]``:
- ``Barriers[Raster]``:
- ``Number of cells between flowlines[Number]``:
- ``Maximum number of segments per flowline[Number]``:
- ``Compute upslope flowlines instead of default downhill flowlines[Boolean]``:
- ``3-D lengths instead of 2-D[Boolean]``:
- ``Use less memory, at a performance penalty[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Output flowline vector layer[Raster]``:
- ``Output flowpath length raster layer[Raster]``:
- ``Output flowline density raster layer[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.flow', elevin, aspin, barin, skip, bound, -u, -3, -m, grass_region_parameter, grass_region_cellsize_parameter, flout, lgout, dsout)
