SOM CLASSIFICATION
==================

Description
-----------

Parameters
----------

- ``InputImage[Raster]``:
- ``ValidityMask[Raster]``:
- ``TrainingProbability[Number]``:
- ``TrainingSetSize[Number]``:
- ``StreamingLines[Number]``:
- ``SizeX[Number]``:
- ``SizeY[Number]``:
- ``NeighborhoodX[Number]``:
- ``NeighborhoodY[Number]``:
- ``NumberIteration[Number]``:
- ``BetaInit[Number]``:
- ``BetaFinal[Number]``:
- ``InitialValue[Number]``:
- ``Available RAM (Mb)[Number]``:
- ``set user defined seed[Number]``:

Outputs
-------

- ``OutputImage[Raster]``:
- ``SOM Map[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:somclassification', -in, -vm, -tp, -ts, -sl, -sx, -sy, -nx, -ny, -ni, -bi, -bf, -iv, -ram, -rand, -out, -som)
