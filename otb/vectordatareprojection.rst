VECTOR DATA REPROJECTION
========================

Description
-----------

Parameters
----------

- ``Input vector data[File]``:
- ``Use image keywords list[Raster]``:
- ``Output Projection choice[Selection]``:
- ``Image used to get projection map[Raster]``:
- ``Output Cartographic Map Projection[Selection]``:
- ``Zone number[Number]``:
- ``Northern Hemisphere[Boolean]``:
- ``EPSG Code[Number]``:

Outputs
-------

- ``Output vector data[File]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:vectordatareprojection', -in.vd, -in.kwl, -out.proj, -out.proj.image.in, -out.proj.user.map, -out.proj.user.map.utm.zone, -out.proj.user.map.utm.northhem, -out.proj.user.map.epsg.code, -out.vd)

	Available options for selection parameters:

	-out.proj(Output Projection choice)
		0 - image
		1 - user

	-out.proj.user.map(Output Cartographic Map Projection)
		0 - utm
		1 - lambert2
		2 - lambert93
		3 - wgs
		4 - epsg
