V.IN.WFS - IMPORT GETFEATURE FROM WFS
=====================================

Description
-----------

Parameters
----------

- ``GetFeature URL starting with 'http'[String]``:
- ``GRASS region extent[Extent]``:

Outputs
-------

- ``Name for output vector map[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:v.in.wfs', wfs, grass_region_parameter, output)
