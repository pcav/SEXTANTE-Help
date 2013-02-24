R.BASINS.FILL - GENERATES WATERSHED SUBBASINS RASTER MAP.
=========================================================

Description
-----------

Parameters
----------

- ``Input coded stream network raster layer[Raster]``:
- ``Input thinned ridge network raster layer[Raster]``:
- ``Number of passes through the dataset[Number]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Watersheds[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.basins.fill', c_map, t_map, number, grass_region_parameter, grass_region_cellsize_parameter, result)
