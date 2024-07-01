## Install code (in a new conda env)
This assumes that `conda` is installed, probably through the [Anaconda program](https://www.anaconda.com/) already.
We will install a fresh environment with all of the tools you will need for this tutorial.  
Note that you may have another install of gmt already that could possibly clash with this.  

My installation # using python.v3.12, and pygmt.v0.10.0

    # addition of specific ghostscript avoids issues with transparencies.  
    
    conda create --name pygmt --channel conda-forge ipython ipykernel numpy pandas gmt pygmt cartopy elevation 
   
*You may want to remove prior `gmt` installs outsides of the python environment, as it may conflict.*

## enter env
    # useful for command-line operations
    conda activate pygmt
    
## Launch Jupyter Notebooks
    # ensure that you're in the directory with '.ipynb' files
    jupyter notebook

Within the notebook proceed with the following order:

**Beginner**

1) Testing_Install.ipynb 
2) Mapping_projections.ipynb
3) Mapping_Overlays.ipynb
4) Shaded_Relief.ipynb

**Advanced**

5) Shaded_Relief-Earthquake.ipynb
6) PlatesBoundariesLandWater.ipynb
