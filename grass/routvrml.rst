R.OUT.VRML - EXPORT A RASTER LAYER TO THE VIRTUAL REALITY MODELING LANGUAGE (VRML)
==================================================================================

Description
-----------

Parameters
----------

- ``Elevation layer[Raster]``:
- ``Color layer[Raster]``:
- ``Vertical exaggeration[Number]``:
- ``GRASS region extent[Extent]``:

Outputs
-------

- ``Output VRML file[File]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.out.vrml', elev, color, exag, grass_region_parameter, output)
