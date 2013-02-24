V.TO.RAST.VALUE - CONVERTS (RASTERIZE) A VECTOR LAYER INTO A RASTER LAYER.
==========================================================================

Description
-----------

Parameters
----------

- ``Input vector layer[Vector]``:
- ``Source of raster values[Selection]``:
- ``Raster value[Number]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------

- ``Rasterized layer[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:v.to.rast.value', input, use, value, grass_region_parameter, grass_region_cellsize_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, output)

	Available options for selection parameters:

	use(Source of raster values)
		0 - val
