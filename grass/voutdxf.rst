V.OUT.DXF - EXPORTS GRASS VECTOR MAP LAYERS TO DXF FILE FORMAT.
===============================================================

Description
-----------

Parameters
----------

- ``Name of input vector map[Vector]``:
- ``GRASS region extent[Extent]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------

- ``Name of DXF output file[File]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:v.out.dxf', input, grass_region_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, output)
