R.SHADED.RELIEF - CREATES SHADED RELIEF FROM AN ELEVATION LAYER (DEM).
======================================================================

Description
-----------

Parameters
----------

- ``Input elevation layer[Raster]``:
- ``Altitude of the sun in degrees above the horizon[Number]``:
- ``Azimuth of the sun in degrees to the east of north[Number]``:
- ``Factor for exaggerating relief[Number]``:
- ``Scale factor for converting horizontal units to elevation units[Number]``:
- ``et scaling factor (applies to lat./long. locations only, none: scale=1)[Selection]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Output shaded relief layer[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.shaded.relief', map, altitude, azimuth, zmult, scale, units, grass_region_parameter, grass_region_cellsize_parameter, shadedmap)

	Available options for selection parameters:

	units(et scaling factor (applies to lat./long. locations only, none: scale=1))
		0 - none
		1 - meters
		2 - feet
