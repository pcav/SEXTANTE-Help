V.CLEAN - TOOLSET FOR CLEANING TOPOLOGY OF VECTOR MAP.
======================================================

Description
-----------

Parameters
----------

- ``Layer to clean[Vector]``:
- ``Cleaning tool[Selection]``:
- ``Threshold[Number]``:
- ``GRASS region extent[Extent]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------

- ``Cleaned vector layer[Vector]``:
- ``Errors layer[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:v.clean', input, tool, thresh, grass_region_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, output, error)

	Available options for selection parameters:

	tool(Cleaning tool)
		0 - break
		1 - snap
		2 - rmdangle
		3 - chdangle
		4 - rmbridge
		5 - chbridge
		6 - rmdupl
		7 - rmdac
		8 - bpol
		9 - prune
		10 - rmarea
		11 - rmline
		12 - rmsa
