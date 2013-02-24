R.SIM.WATER - OVERLAND FLOW HYDROLOGIC SIMULATION USING PATH SAMPLING METHOD (SIMWE).
=====================================================================================

Description
-----------

Parameters
----------

- ``Name of the elevation raster map [m][Raster]``:
- ``Name of the x-derivatives raster map [m/m][Raster]``:
- ``Name of the y-derivatives raster map [m/m][Raster]``:
- ``Name of the rainfall excess rate (rain-infilt) raster map [mm/hr][Raster]``:
- ``Rainfall excess rate unique value [mm/hr][String]``:
- ``Name of the runoff infiltration rate raster map [mm/hr][Raster]``:
- ``Runoff infiltration rate unique value [mm/hr][String]``:
- ``Name of the Mannings n raster map[Raster]``:
- ``Mannings n unique value[String]``:
- ``Name of the flow controls raster map (permeability ratio 0-1)[Raster]``:
- ``Number of walkers, default is twice the no. of cells[String]``:
- ``Time used for iterations [minutes][String]``:
- ``Time interval for creating output maps [minutes][String]``:
- ``Water diffusion constant[String]``:
- ``Threshold water depth [m] (diffusion increases after this water depth is reached)[String]``:
- ``Diffusion increase constant[String]``:
- ``Weighting factor for water flow velocity vector[String]``:
- ``Time-series output[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Output water depth raster map [m][Raster]``:
- ``Output water discharge raster map [m3/s][Raster]``:
- ``Output simulation error raster map [m][Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.sim.water', elevin, dxin, dyin, rain, rain_val, infil, infil_val, manin, manin_val, traps, nwalk, niter, outiter, diffc, hmax, halpha, hbeta, -t, grass_region_parameter, grass_region_cellsize_parameter, depth, disch, err)
