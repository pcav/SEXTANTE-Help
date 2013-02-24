SHAPES BUFFER
=============

Description
-----------

Parameters
----------

- ``Shapes[Vector]``:
- ``Buffer Distance[Selection]``:
- ``Buffer Distance (Fixed)[Number]``:
- ``Buffer Distance (Attribute)[TableField]``:
- ``Scaling Factor for Attribute Value[Number]``:
- ``Number of Buffer Zones[Number]``:
- ``Circle Point Distance [Degree][Number]``:
- ``Dissolve Buffers[Boolean]``:

Outputs
-------

- ``Buffer[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('saga:shapesbuffer', shapes, buf_type, buf_dist, buf_field, buf_scale, buf_zones, dcircle, dissolve, buffer)

	Available options for selection parameters:

	buf_type(Buffer Distance)
		0 - [0] fixed value
		1 - [1] attribute field
