CARTOGRAPHIC TO GEOGRAPHIC COORDINATES CONVERSION
=================================================

Description
-----------

Parameters
----------

- ``X cartographic coordinates[Number]``:
- ``Y cartographic coordinates[Number]``:
- ``Output Cartographic Map Projection[Selection]``:
- ``Zone number[Number]``:
- ``Northern Hemisphere[Boolean]``:
- ``EPSG Code[Number]``:
- ``Output long[Number]``:
- ``Output lat[Number]``:

Outputs
-------


See also
---------


Console usage
-------------


::

	sextante.runalg('otb:cartographictogeographiccoordinatesconversion', -carto.x, -carto.y, -mapproj, -mapproj.utm.zone, -mapproj.utm.northhem, -mapproj.epsg.code, -long, -lat)

	Available options for selection parameters:

	-mapproj(Output Cartographic Map Projection)
		0 - utm
		1 - lambert2
		2 - lambert93
		3 - wgs
		4 - epsg
