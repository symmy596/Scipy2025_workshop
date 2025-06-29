# Geospatial data manipulation and visualisation

![alt text](https://github.com/symmy596/Scipy2025_workshop/blob/main/resources/assets/river_topography.png) 

## Download Tutorial Materials

This GitHub repository is all that is needed in terms of tutorial content. The simplest solution is to download the material using this link:

https://github.com/symmy596/Scipy2025_workshop/archive/refs/heads/main.zip

If you are familiar with Git, you can also clone this repository with:

```
$ git clone https://github.com/symmy596/Scipy2025_workshop.git
```

It will create a new folder named `Scipy2025_workshop` with all the content you will need.

There are a number of datasets required for these tutorials. These will need to all be downloaded prior to the tutorial and placed in the resources folder.

## Data

Downsampled data that will allow you to complete the tutorial can be found in the `resources/data directory`. These were generated from the datasets listed below. With a sufficiently powerful laptop you will be able to use these datasets to generate more detailed versions of the maps that we will make in this tutorial. However for ease and simplicity, please feel free to use the 
downsampled data in the repo. 

#### Tutorial 1 Vector Data

- [Hydrorivers](https://www.hydrosheds.org/products/hydrorivers)
- [Hydrobasins](https://www.hydrosheds.org/products/hydrobasins)
- [Natural Earth Country Boundaries](https://github.com/nvkelso/natural-earth-vector/blob/master/10m_cultural/ne_10m_admin_0_countries.shps)

#### Tutorial 2 Raster

- [Forests](https://github.com/globalmaps/gm_ve_v1)
- [Natural Earth Country Boundaries](https://github.com/nvkelso/natural-earth-vector/blob/master/10m_cultural/ne_10m_admin_0_countries.shps)

#### Tutorial 3 Advanced Rasters

- [Topography](https://www.ngdc.noaa.gov/mgg/global/relief/ETOPO1/data/bedrock/grid_registered/georeferenced_tiff/)
- [Natural Earth Country Boundaries](https://github.com/nvkelso/natural-earth-vector/blob/master/10m_cultural/ne_10m_admin_0_countries.shps)


### Install Packages

To be able to run the examples, demos and exercises, you must have the following packages installed:

The following libraries are required to run the workshop

- geopandas==0.10.2
- pandas==1.4.2
- numpy==1.21.5
- shapely==1.8.0
- matplotlib==3.5.1
- cartopy==0.20.2
- rasterio==1.2.10
- rioxarray==0.11.1
- gdal==3.5.2
- xarray==2022.9.0
- pyarrow==9.0.0

If you are using Anaconda, you can use the Anaconda Prompt (Windows) or Terminal.app (macOS) to create an environment with the necessary packages:

1. Open the Anaconda Prompt or Terminal.app using the below instructions:
    - **Windows**: Click Start and search for "Anaconda Prompt". Click on the application to launch a new Anaconda Prompt window.
    - **macOS**: Open Spotlight Search (using Cmd+Space) and type "Terminal.app". Click on the application to launch a new Terminal.app window.   

2. Create a new Anaconda virtual environment by executing the below command in the application window you opened in step 1 above.

    ```
    conda create -n pythonmaps-tutorial -c conda-forge jupyter geopandas==0.10.2 pandas==1.4.2 numpy==1.21.5 shapely==1.8.0 matplotlib==3.5.1 cartopy==0.20.2 rasterio==1.2.10 rioxarray==0.11.1 xarray==2022.9.0 pyarrow==9.0.0
    ```

3. To test your installation, please execute the `check_env.py` script in the environment where you have installed the requirements. If you created an Anaconda environment using the instructions above, keep the application window that you opened in step 1 active (or launch the platform specific application again -- Anaconda Prompt for Windows or Terminal.app for macOS), navigate to where you have this GitHub repository, and type:

    ```
    $ conda activate pythonmaps-tutorial
    $ python check_env.py
    ```

You should see a window pop up with a plot that looks vaguely like a smiley face.
