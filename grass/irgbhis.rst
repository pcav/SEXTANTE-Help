I.RGB.HIS - TRANSFORMS RASTER MAPS FROM RGB (RED-GREEN-BLUE) COLOR SPACE TO HIS (HUE-INTENSITY-SATURATION) COLOR SPACE.
=======================================================================================================================

Description
-----------

Parameters
----------

- ``Name for input raster map (red)[Raster]``:
- ``Name for input raster map (green)[Raster]``:
- ``Name for input raster map (blue)[Raster]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Name of output raster map (hue)[Raster]``:
- ``Name of output raster map (intensity)[Raster]``:
- ``Name of output raster map (saturation)[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:i.rgb.his', red_output, green_output, blue_output, grass_region_parameter, grass_region_cellsize_parameter, hue_input, intensity_input, saturation_input)
