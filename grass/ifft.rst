I.FFT - FAST FOURIER TRANSFORM (FFT) FOR IMAGE PROCESSING.
==========================================================

Description
-----------

Parameters
----------

- ``Name of input raster map[Raster]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Name for output real part arrays stored as raster map[Raster]``:
- ``Name for output imaginary part arrays stored as raster map[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:i.fft', input_image, grass_region_parameter, grass_region_cellsize_parameter, real_image, imaginary_image)
