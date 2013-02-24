IMAGE RESAMPLING WITH A RIGID TRANSFORM
=======================================

Description
-----------

Parameters
----------

- ``Input image[Raster]``:
- ``Type of transformation[Selection]``:
- ``X scaling[Number]``:
- ``Y scaling[Number]``:
- ``The X translation (in physical units)[Number]``:
- ``The Y translation (in physical units)[Number]``:
- ``Rotation angle[Number]``:
- ``X scaling[Number]``:
- ``Y scaling[Number]``:
- ``Interpolation[Selection]``:
- ``Radius for bicubic interpolation[Number]``:
- ``Available RAM (Mb)[Number]``:

Outputs
-------

- ``Output image[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:imageresamplingwitharigidtransform', -in, -transform.type, -transform.type.id.scalex, -transform.type.id.scaley, -transform.type.translation.tx, -transform.type.translation.ty, -transform.type.rotation.angle, -transform.type.rotation.scalex, -transform.type.rotation.scaley, -interpolator, -interpolator.bco.radius, -ram, -out)

	Available options for selection parameters:

	-transform.type(Type of transformation)
		0 - id
		1 - translation
		2 - rotation

	-interpolator(Interpolation)
		0 - nn
		1 - linear
		2 - bco
