R.OUT.PPM - CONVERTS A RASTER LAYER TO A PPM IMAGE FILE AT THE PIXEL RESOLUTION OF THE CURRENTLY DEFINED REGION.
================================================================================================================

Description
-----------

Parameters
----------

- ``Input raster layer[Raster]``:
- ``Output greyscale instead of color[Boolean]``:
- ``GRASS region extent[Extent]``:

Outputs
-------

- ``Output PPM file[File]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.out.ppm', input, -g, grass_region_parameter, output)
