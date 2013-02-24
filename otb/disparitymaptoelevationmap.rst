DISPARITY MAP TO ELEVATION MAP
==============================

Description
-----------

Parameters
----------

- ``Input disparity map[Raster]``:
- ``Left sensor image[Raster]``:
- ``Right sensor image[Raster]``:
- ``Left Grid[Raster]``:
- ``Right Grid[Raster]``:
- ``Disparity mask[Raster]``:
- ``DEM step[Number]``:
- ``Minimum elevation expected[Number]``:
- ``Maximum elevation expected[Number]``:
- ``Elevation management[Selection]``:
- ``DEM directory[File]``:
- ``Geoid File[File]``:
- ``Average Elevation[Number]``:
- ``Available RAM (Mb)[Number]``:

Outputs
-------

- ``Output elevation map[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:disparitymaptoelevationmap', -io.in, -io.left, -io.right, -io.lgrid, -io.rgrid, -io.mask, -step, -hmin, -hmax, -elev, -elev.dem.path, -elev.dem.geoid, -elev.average.value, -ram, -io.out)

	Available options for selection parameters:

	-elev(Elevation management)
		0 - dem
		1 - average
