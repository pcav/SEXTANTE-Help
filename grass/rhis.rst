R.HIS - GENERATES RED, GREEN AND BLUE RASTER LAYERS COMBINING HUE, INTENSITY AND SATURATION (HIS) VALUES FROM USER-SPECIFIED INPUT RASTER LAYERS.
=================================================================================================================================================

Description
-----------

Parameters
----------

- ``Hue[Raster]``:
- ``Intensity[Raster]``:
- ``Saturation[Raster]``:
- ``Respect NULL values while drawing[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Red[Raster]``:
- ``Green[Raster]``:
- ``Blue[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.his', h_map, i_map, s_map, -n, grass_region_parameter, grass_region_cellsize_parameter, r_map, g_map, b_map)
