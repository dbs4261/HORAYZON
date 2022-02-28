# HORAYZON

# General Information
Package to compute terrain parameters horizon, sky view factor and slope angle/aspect from high-resolution elevation data. Horizon computation is based on the high-performance ray-tracing library Embree. The package is written in Python, Cython and C++.

# Dependencies

## Python packages

Source code:
- numpy
- cython
- scipy
- geographiclib
- pyproj
- gdal
- shapely
- fiona
- pygeos
- scikit-image

Application:
- xarray
- matplotlib
- netcdf4
- rasterio

Optional for remote terrain simplification:
- trimesh

## Further dependencies
- Intel&copy; Embree with Intel Threading Building Blocks (TBB) and GLFW. Source code and compilation instructions can be found here: https://github.com/embree/embree
- NetCDF4 C++. Source code and compilation instructions can be found here: https://github.com/Unidata/netcdf-cxx4
- hmm. Optional &ndash; only required if remote terrain simplification is needed in case of elevation data with very high (<5 m) resolution. Source code and compilation instructions can be found here: https://github.com/fogleman/hmm

# Installation

# Required data

# Usage

# Example output

# Reference
Link to Geoscientific Model Development [manuscript](https://www.geoscientific-model-development.net)

# Support 
In case of issues or questions, please contact Christian Steger (christian.steger@env.ethz.ch).