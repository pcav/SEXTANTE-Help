WATERSHED SEGMENTATION (LARGE-SCALE, VECTOR OUTPUT)
===================================================

Description
-----------

Parameters
----------

- ``Input Image[Raster]``:
- ``Depth Threshold[Number]``:
- ``Flood level[Number]``:
- ``Mask Image[Vector]``:
- ``8-neighbor connectivity[Boolean]``:
- ``Stitch polygons[Boolean]``:
- ``Minimum object size[Number]``:
- ``Simplify polygons[Number]``:
- ``Layer name [String]``:
- ``Tile size[Number]``:
- ``Starting geometry index[Number]``:
- ``Writing mode (update file/overwrite file/overwrite layer/update layer)[Selection]``:
- ``OGR options for layer creation[String]``:

Outputs
-------

- ``Output vector file[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:watershedsegmentationlargescalevectoroutput', -filter watershed -in, -filter.watershed.threshold, -filter.watershed.level, -mode.vector.inmask, -mode.vector.neighbor, -mode.vector.stitch, -mode.vector.minsize, -mode.vector.simplify, -mode.vector.layername, -mode.vector.tilesize, -mode.vector.startlabel, -mode.vector.outmode, -mode.vector.ogroptions, -mode vector -mode.vector.out)

	Available options for selection parameters:

	-mode.vector.outmode(Writing mode (update file/overwrite file/overwrite layer/update layer))
		0 - ulco
		1 - ovw
		2 - ulovw
		3 - ulu
