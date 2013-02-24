V.TRANSFORM - PERFORMS AN AFFINE TRANSFORMATION (SHIFT, SCALE AND ROTATE, OR GPCS) ON A VECTOR LAYER.
=====================================================================================================

Description
-----------

Parameters
----------

- ``Name of input vector map[Vector]``:
- ``X shift[Number]``:
- ``Y shift[Number]``:
- ``Z shift[Number]``:
- ``X scale[Number]``:
- ``Y scale[Number]``:
- ``Z scale[Number]``:
- ``Rotation around z axis in degrees counterclockwise[Number]``:
- ``GRASS region extent[Extent]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------

- ``Transformed layer[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:v.transform', input, xshift, yshift, zshift, xscale, yscale, zscale, zrot, grass_region_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, output)
