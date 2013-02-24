I.IFFT - INVERSE FAST FOURIER TRANSFORM (IFFT) FOR IMAGE PROCESSING.
====================================================================

Description
-----------

Parameters
----------

- ``Name of input raster map (image fft, real part)[Raster]``:
- ``Name of input raster map (image fft, imaginary part)[Raster]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Name for output raster map[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:i.ifft', real_image, imaginary_image, grass_region_parameter, grass_region_cellsize_parameter, output_image)
