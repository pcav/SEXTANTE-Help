V.DB.SELECT - PRINTS VECTOR MAP ATTRIBUTES
==========================================

Description
-----------

Parameters
----------

- ``Input vector map [Vector]``:
- ``Layer Number[Number]``:
- ``Name of attribute column(s), comma separated[String]``:
- ``Do not include column names in output[Boolean]``:
- ``Output field separator[String]``:
- ``WHERE conditions of SQL statement without 'where' keyword[String]``:
- ``Output vertical record separator[String]``:
- ``Null value indicator[String]``:
- ``Vertical output (instead of horizontal)[Boolean]``:
- ``Print minimal region extent of selected vector features instead of attributes[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------

- ``Output file[File]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:v.db.select', map, layer, columns, -c, fs, where, vs, nv, -v, -r, grass_region_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, file)
