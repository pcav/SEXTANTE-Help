PIXEL-WISE BLOCK-MATCHING
=========================

Description
-----------

Parameters
----------

- ``Left input image[Raster]``:
- ``Right input image[Raster]``:
- ``Output optimal metric values as well[Boolean]``:
- ``Discard left pixels from mask image[Raster]``:
- ``Discard right pixels from mask image[Raster]``:
- ``Discard pixels with no-data value[Number]``:
- ``Discard pixels with low local variance[Number]``:
- ``Block-matching metric[Selection]``:
- ``p value[Number]``:
- ``Radius of blocks[Number]``:
- ``Minimum horizontal disparity[Number]``:
- ``Maximum horizontal disparity[Number]``:
- ``Minimum vertical disparity[Number]``:
- ``Maximum vertical disparity[Number]``:
- ``Sub-pixel interpolation[Selection]``:
- ``Radius[Number]``:
- ``Incoherence threshold[Number]``:
- ``Initial disparities[Selection]``:
- ``Horizontal initial disparity[Number]``:
- ``Vertical initial disparity[Number]``:
- ``Horizontal exploration radius[Number]``:
- ``Vertical exploration radius[Number]``:
- ``Horizontal initial disparity map[Raster]``:
- ``Vertical initial disparity map[Raster]``:
- ``Horizontal exploration radius[Number]``:
- ``Vertical exploration radius[Number]``:
- ``Available RAM (Mb)[Number]``:

Outputs
-------

- ``The output disparity map[Raster]``:
- ``The left output mask corresponding to all criterions[Raster]``:
- ``The right output mask corresponding to all criterions[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:pixelwiseblockmatching', -io.inleft, -io.inright, -io.outmetric, -mask.inleft, -mask.inright, -mask.nodata, -mask.variancet, -bm.metric, -bm.metric.lp.p, -bm.radius, -bm.minhd, -bm.maxhd, -bm.minvd, -bm.maxvd, -bm.subpixel, -bm.medianfilter.radius, -bm.medianfilter.incoherence, -bm.initdisp, -bm.initdisp.uniform.hdisp, -bm.initdisp.uniform.vdisp, -bm.initdisp.uniform.hrad, -bm.initdisp.uniform.vrad, -bm.initdisp.maps.hmap, -bm.initdisp.maps.vmap, -bm.initdisp.maps.hrad, -bm.initdisp.maps.vrad, -ram, -io.out, -io.outmaskleft, -io.outmaskright)

	Available options for selection parameters:

	-bm.metric(Block-matching metric)
		0 - ssd
		1 - ncc
		2 - lp

	-bm.subpixel(Sub-pixel interpolation)
		0 - none
		1 - parabolic
		2 - triangular
		3 - dichotomy

	-bm.initdisp(Initial disparities)
		0 - none
		1 - uniform
		2 - maps
