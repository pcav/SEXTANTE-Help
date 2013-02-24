V.IN.DXF - CONVERTS FILES IN DXF FORMAT TO GRASS VECTOR MAP FORMAT.
===================================================================

Description
-----------

Parameters
----------

- ``Name of input DXF file[File]``:
- ``List of layers to import[String]``:
- ``Ignore the map extent of DXF file[Boolean]``:
- ``Do not create attribute tables[Boolean]``:
- ``Import polyface meshes as 3D wire frame[Boolean]``:
- ``List available layers and exit[Boolean]``:
- ``Invert selection by layers (don't import layers in list)[Boolean]``:
- ``Import all objects into one layer[Boolean]``:
- ``GRASS region extent[Extent]``:

Outputs
-------

- ``Name for output vector map[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:v.in.dxf', input, layers, -e, -t, -f, -l, -i, -1, grass_region_parameter, output)
