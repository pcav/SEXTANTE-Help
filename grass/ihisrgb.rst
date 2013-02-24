I.HIS.RGB - TRANSFORMS RASTER MAPS FROM HIS (HUE-INTENSITY-SATURATION) COLOR SPACE TO RGB (RED-GREEN-BLUE) COLOR SPACE.
=======================================================================================================================

Description
-----------

Parameters
----------

- ``Name of input raster map (hue)[Raster]``:
- ``Name of input raster map (intensity)[Raster]``:
- ``Name of input raster map (saturation)[Raster]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Name for output raster map (red)[Raster]``:
- ``Name for output raster map (green)[Raster]``:
- ``Name for output raster map (blue)[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:i.his.rgb', hue_input, intensity_input, saturation_input, grass_region_parameter, grass_region_cellsize_parameter, red_output, green_output, blue_output)
