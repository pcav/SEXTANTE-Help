V.MKGRID - CREATES A GRASS VECTOR LAYER OF A USER-DEFINED GRID.
===============================================================

Description
-----------

Parameters
----------

- ``Number of rows and columns in grid[String]``:
- ``Where to place the grid[Selection]``:
- ``Lower left easting and northing coordinates of map[String]``:
- ``Width and height of boxes in grid[String]``:
- ``Angle of rotation (in degrees counter-clockwise)[String]``:
- ``Create grid of points instead of areas and centroids[Boolean]``:
- ``GRASS region extent[Extent]``:

Outputs
-------

- ``Output grid[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:v.mkgrid', grid, position, coor, box, angle, -p, grass_region_parameter, map)

	Available options for selection parameters:

	position(Where to place the grid)
		0 - coor
