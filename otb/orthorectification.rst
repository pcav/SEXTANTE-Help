ORTHO-RECTIFICATION
===================

Description
-----------

Parameters
----------

- ``Input Image[Raster]``:
- ``Output Cartographic Map Projection[Selection]``:
- ``Zone number[Number]``:
- ``Northern Hemisphere[Boolean]``:
- ``EPSG Code[Number]``:
- ``Parameters estimation modes[Selection]``:
- ``Upper Left X[Number]``:
- ``Upper Left Y[Number]``:
- ``Size X[Number]``:
- ``Size Y[Number]``:
- ``Pixel Size X[Number]``:
- ``Pixel Size Y[Number]``:
- ``Force isotropic spacing by default[Boolean]``:
- ``Default pixel value[Number]``:
- ``Elevation management[Selection]``:
- ``DEM directory[File]``:
- ``Geoid File[File]``:
- ``Average Elevation[Number]``:
- ``Interpolation[Selection]``:
- ``Radius for bicubic interpolation[Number]``:
- ``RPC modeling (points per axis)[Number]``:
- ``Available RAM (Mb)[Number]``:
- ``Resampling grid spacing[Number]``:

Outputs
-------

- ``Output Image[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:orthorectification', -io.in, -map, -map.utm.zone, -map.utm.northhem, -map.epsg.code, -outputs.mode, -outputs.ulx, -outputs.uly, -outputs.sizex, -outputs.sizey, -outputs.spacingx, -outputs.spacingy, -outputs.isotropic, -outputs.default, -elev, -elev.dem.path, -elev.dem.geoid, -elev.average.value, -interpolator, -interpolator.bco.radius, -opt.rpc, -opt.ram, -opt.gridspacing, -io.out)

	Available options for selection parameters:

	-map(Output Cartographic Map Projection)
		0 - utm
		1 - lambert2
		2 - lambert93
		3 - wgs
		4 - epsg

	-outputs.mode(Parameters estimation modes)
		0 - auto
		1 - autosize
		2 - autospacing

	-elev(Elevation management)
		0 - dem
		1 - average

	-interpolator(Interpolation)
		0 - nn
		1 - linear
		2 - bco
