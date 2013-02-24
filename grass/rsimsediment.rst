R.SIM.SEDIMENT - SEDIMENT TRANSPORT AND EROSION/DEPOSITION SIMULATION USING PATH SAMPLING METHOD (SIMWE).
=========================================================================================================

Description
-----------

Parameters
----------

- ``Name of the elevation raster map [m][Raster]``:
- ``Name of the water depth raster map [m][Raster]``:
- ``Name of the x-derivatives raster map [m/m][Raster]``:
- ``Name of the y-derivatives raster map [m/m][Raster]``:
- ``Name of the detachment capacity coefficient raster map [s/m][Raster]``:
- ``Name of the transport capacity coefficient raster map [s][Raster]``:
- ``Name of the critical shear stress raster map [Pa][Raster]``:
- ``Name of the Mannings n raster map[Raster]``:
- ``Name of the Mannings n value[Number]``:
- ``Number of walkers[Number]``:
- ``Time used for iterations [minutes][Number]``:
- ``Time interval for creating output maps [minutes][Number]``:
- ``Water diffusion constant[Number]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Output transport capacity raster map [kg/ms][Raster]``:
- ``Output transp.limited erosion-deposition raster map [kg/m2s][Raster]``:
- ``Output sediment concentration raster map [particle/m3][Raster]``:
- ``Output sediment flux raster map [kg/ms][Raster]``:
- ``Output erosion-deposition raster map [kg/m2s][Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.sim.sediment', elevin, wdepth, dxin, dyin, detin, tranin, tauin, manin, maninval, nwalk, niter, outiter, diffc, grass_region_parameter, grass_region_cellsize_parameter, tc, et, conc, flux, erdep)
