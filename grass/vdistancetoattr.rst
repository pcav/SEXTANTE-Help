V.DISTANCE.TOATTR - FINDS THE NEAREST ELEMENT IN VECTOR MAP 'TO' FOR ELEMENTS IN VECTOR MAP 'FROM'.
===================================================================================================

Description
-----------

Parameters
----------

- ``"from" input layer[Vector]``:
- ``"to" input layer[Vector]``:
- ``Values describing the relation between two nearest features[Selection]``:
- ``Column where values specified by 'upload' option will be uploaded[TableField]``:
- ``Column name of nearest feature[TableField]``:
- ``Calculate distances to all features within the threshold[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------

- ``Output layer[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:v.distance.toattr', from, to, upload, column, to_column, -a, grass_region_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, output)

	Available options for selection parameters:

	upload(Values describing the relation between two nearest features)
		0 - to_attr
