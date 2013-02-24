V.SAMPLE - SAMPLES A RASTER LAYER AT VECTOR POINT LOCATIONS.
============================================================

Description
-----------

Parameters
----------

- ``Vector layer defining sample points[Vector]``:
- ``Vector layer attribute column to use for comparison[TableField]``:
- ``Raster map to be sampled[Raster]``:
- ``Sampled raster values will be multiplied by this factor[Number]``:
- ``Bilinear interpolation (default is nearest neighbor)[Boolean]``:
- ``Cubic convolution interpolation (default is nearest neighbor)[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------

- ``Output vector layer[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:v.sample', input, column, raster, z, -b, -c, grass_region_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, output)
