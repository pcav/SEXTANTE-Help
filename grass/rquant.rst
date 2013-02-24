R.QUANT - PRODUCES THE QUANTIZATION FILE FOR A FLOATING-POINT MAP.
==================================================================

Description
-----------

Parameters
----------

- ``Raster layer(s) to be quantized[MultipleInput]``:
- ``Base layer to take quant rules from[Raster]``:
- ``Floating point range: dmin,dmax[Range]``:
- ``Integer range: min,max[Range]``:
- ``Truncate floating point data[Boolean]``:
- ``Round floating point data[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------


See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.quant', input, basemap, fprange, range, -t, -r, grass_region_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter)
