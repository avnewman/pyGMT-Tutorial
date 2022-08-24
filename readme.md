## Install code (in a new conda env)
We will install a fresh environment with all of the tools you will need for this tutorial.  Note that you may have another install of
gmt already that could possibly clash with this.  

    # my installation
    conda create --name Maps  --channel conda-forge python=3.9 ipython ipykernel numpy pandas xarray netcdf4 packaging gmt pygmt cartopy elevation

## enter env
    # useful for comman-line operations
    conda activate Maps
