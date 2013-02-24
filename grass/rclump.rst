R.CLUMP - RECATEGORIZES DATA IN A RASTER MAP BY GROUPING CELLS THAT FORM PHYSICALLY DISCRETE AREAS INTO UNIQUE CATEGORIES.
==========================================================================================================================

Description
-----------

Parameters
----------

- ``Input layer[Raster]``:
- ``Title for output raster map[String]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Recategorized layer[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.clump', input, title, grass_region_parameter, grass_region_cellsize_parameter, output)
