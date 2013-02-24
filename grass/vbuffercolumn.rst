V.BUFFER.COLUMN - CREATES A BUFFER AROUND FEATURES OF GIVEN TYPE.
=================================================================

Description
-----------

Parameters
----------

- ``Input vector layer[Vector]``:
- ``Name of column to use for buffer distances[TableField]``:
- ``Scaling factor for attribute column values[Number]``:
- ``Maximum distance between theoretical arc and polygon segments as multiple of buffer[String]``:
- ``Make outside corners straight[Boolean]``:
- ``Don't make caps at the ends of polylines[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------

- ``Output buffer[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:v.buffer.column', input, bufcolumn, scale, tolerance, -s, -c, grass_region_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, output)
