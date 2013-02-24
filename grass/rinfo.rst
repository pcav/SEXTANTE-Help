R.INFO - OUTPUT BASIC INFORMATION ABOUT A RASTER LAYER.
=======================================================

Description
-----------

Parameters
----------

- ``Raster layer[Raster]``:
- ``Print range only[Boolean]``:
- ``Print raster map resolution (NS-res, EW-res) only[Boolean]``:
- ``Print raster map type only[Boolean]``:
- ``Print map region only[Boolean]``:
- ``Print raster history instead of info[Boolean]``:
- ``Print raster map data units only[Boolean]``:
- ``Print raster map vertical datum only[Boolean]``:
- ``Print map title only[Boolean]``:
- ``Print raster map timestamp (day.month.year hour:minute:seconds) only[Boolean]``:
- ``GRASS region extent[Extent]``:

Outputs
-------

- ``Layer info[HTML]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.info', map, -r, -s, -t, -g, -h, -u, -d, -m, -p, grass_region_parameter, html)
