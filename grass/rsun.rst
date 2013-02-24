R.SUN - SOLAR IRRADIANCE AND IRRADIATION MODEL.
===============================================

Description
-----------

Parameters
----------

- ``Elevation layer [meters][Raster]``:
- ``Aspect layer [decimal degrees][Raster]``:
- ``Name of the input slope raster map (terrain slope or solar panel inclination) [decimal degrees][Raster]``:
- ``Name of the Linke atmospheric turbidity coefficient input raster map[Raster]``:
- ``Name of the ground albedo coefficient input raster map[Raster]``:
- ``Name of input raster map containing latitudes [decimal degrees][Raster]``:
- ``Name of input raster map containing longitudes [decimal degrees][Raster]``:
- ``Name of real-sky beam radiation coefficient input raster map[Raster]``:
- ``Name of real-sky diffuse radiation coefficient input raster map[Raster]``:
- ``No. of day of the year (1-365)[Number]``:
- ``Time step when computing all-day radiation sums [decimal hours][Number]``:
- ``Declination value (overriding the internally computed value) [radians][Number]``:
- ``Sampling distance step coefficient (0.5-1.5)[Number]``:
- ``Incorporate the shadowing effect of terrain[Boolean]``:
- ``Use the low-memory version of the program[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Output irradiation layer [Wh.m-2.day-1][Raster]``:
- ``Output insolation time layer [h][Raster]``:
- ``Outpu diffuse irradiation layer [Wh.m-2.day-1][Raster]``:
- ``Output ground reflected irradiation layer [Wh.m-2.day-1][Raster]``:
- ``Output global (total) irradiance/irradiation layer [Wh.m-2.day-1][Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.sun', elevin, aspin, slopein, linkein, albedo, latin, longin, coefbh, coefdh, day, step, declin, dist, -s, -m, grass_region_parameter, grass_region_cellsize_parameter, beam_rad, insol_time, diff_rad, refl_rad, glob_rad)
