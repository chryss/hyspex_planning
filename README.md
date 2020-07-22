# HySpex Flightplanning

Collection of Jupyter Notebooks and scripts to support the aerial hyperspectral surveys carried out by the Hylab and Alaska EPSCoR Fire and Ice (https://www.alaska.edu/epscor/fire-and-ice/) teams at the University of Alaska Fairbanks.

This code is not meant to be published, so I (CW) affixed no license. There's nothing secret about it, though. 

Clone this repository (or download the files).

Requirements: Python packages `geopandas`, `shapely`, `fiona` as well a  `jupyter`, `matplotlib`. 

Contents:

* [HySpex flight planning](https://github.com/chryss/hyspex_planning/blob/master/HySpex%20flight%20planning.ipynb): Replacement for planning spreadsheet (supplied by NEO). Supports planning flight height as a function of camera, target area elevation, and desired spatial resolution of the imagery. Specify start point, flight line length, number & direction and generates GPX file containing the flightline endpoint coordinates in flight order
* [HySpex line shapefile re-jigger](https://github.com/chryss/hyspex_planning/blob/master/HySpex%20line%20shapefile%20re-jigger.ipynb): Load a line shapefile, reproject (to WGS84) and re-order line endpoints in whatever order is desired. 
* [Boresight averaging](Boresight_averaging.ipynb): Exploratory analysis of boresight values determined from pairs of flightlines. 
