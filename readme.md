## Install code (in a new conda env)
This assumes that `conda` is installed, probably through the [Anaconda program](https://www.anaconda.com/) already.
We will install a fresh environment with all of the tools you will need for this tutorial.  
Note that you may have another install of gmt already that could possibly clash with this.  

## My installation 
    # tested using python.v3.13, and pygmt.v0.13.0
    conda create --name pygmt --channel conda-forge ipython ipykernel jupyter numpy pandas gmt pygmt cartopy elevation 
   
*You may want to remove prior `gmt` installs outsides of the python environment, as it may conflict.*

## enter env
    # useful for command-line operations
    conda activate pygmt

## Install this tutorial
    # I use a Mac/Linux terminal to do this
    # make and change to ~a/directory/that/you/want/to/save/this/in
    # e.g.
    mkdir ~/pygmt_tutorial
    cd ~/pygmt_tutorial
    # get the tutorial 
    git clone git@github.com:avnewman/pyGMT-Tutorial.git

## Launch Jupyter Notebooks
    # ensure that you're in the directory with '.ipynb' files
    jupyter notebook

Within the notebook proceed with the following order:

**Beginner**

1) 01_Testing_Install.ipynb 
2) 02_Mapping_projections.ipynb
3) 03_Mapping_Overlays.ipynb
4) 04_Shaded_Relief.ipynb

**Advanced**

5) 05_Shaded_Relief-Earthquake.ipynb
6) 06_PlatesBoundariesLandWater.ipynb
