R.PATCH - CREATES A COMPOSITE RASTER LAYER BY USING ONE (OR MORE) LAYER(S) TO FILL IN AREAS OF "NO DATA" IN ANOTHER MAP LAYER.
==============================================================================================================================

Description
-----------

Parameters
----------

- ``Raster layers to be patched together[MultipleInput]``:
- ``Use zero (0) for transparency instead of NULL[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Result[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.patch', input, -z, grass_region_parameter, grass_region_cellsize_parameter, output)
