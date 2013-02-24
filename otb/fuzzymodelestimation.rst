FUZZY MODEL ESTIMATION
======================

Description
-----------

Parameters
----------

- ``Input Positive Vector Data[Vector]``:
- ``Input Negative Vector Data[Vector]``:
- ``Criterion[String]``:
- ``Weighting[Number]``:
- ``initialization model[File]``:
- ``Maximum number of iterations[Number]``:
- ``Optimizer Observer[Boolean]``:

Outputs
-------

- ``Output filename[File]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:fuzzymodelestimation', -psin, -nsin, -cri, -wgt, -initmod, -maxnbit, -optobs, -out)
