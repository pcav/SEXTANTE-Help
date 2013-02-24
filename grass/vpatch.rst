V.PATCH - CREATE A NEW VECTOR MAP LAYER BY COMBINING OTHER VECTOR MAP LAYERS.
=============================================================================

Description
-----------

Parameters
----------

- ``Input layers[MultipleInput]``:
- ``Copy also attribute table[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------

- ``Name for output vector map[Vector]``:
- ``Bounding boxes[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:v.patch', input, -e, grass_region_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, output, bbox)
