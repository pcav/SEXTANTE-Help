IMAGES COMPARAISON
==================

Description
-----------

Parameters
----------

- ``Reference image[Raster]``:
- ``Reference image channel[Number]``:
- ``Measured image[Raster]``:
- ``Measured image channel[Number]``:
- ``Start X[Number]``:
- ``Start Y[Number]``:
- ``Size X[Number]``:
- ``Size Y[Number]``:
- ``MSE[Number]``:
- ``MAE[Number]``:
- ``PSNR[Number]``:

Outputs
-------


See also
---------


Console usage
-------------


::

	sextante.runalg('otb:imagescomparaison', -ref.in, -ref.channel, -meas.in, -meas.channel, -roi.startx, -roi.starty, -roi.sizex, -roi.sizey, -mse, -mae, -psnr)
