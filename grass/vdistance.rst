V.DISTANCE - FINDS THE NEAREST ELEMENT IN VECTOR MAP 'TO' FOR ELEMENTS IN VECTOR MAP 'FROM'.
============================================================================================

Description
-----------

Parameters
----------

- ``"from" input layer[Vector]``:
- ``"to" input layer[Vector]``:
- ``Values describing the relation between two nearest features[Selection]``:
- ``Column where values specified by 'upload' option will be uploaded[TableField]``:
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

	sextante.runalg('grass:v.distance', from, to, upload, column, -a, grass_region_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, output)

	Available options for selection parameters:

	upload(Values describing the relation between two nearest features)
		0 - cat
		1 - dist
		2 - to_x
		3 - to_y
		4 - to_along
		5 - to_angle
