# NOAA data set interpretation

If you go to [here](https://www.ncdc.noaa.gov/cdo-web/datasets/GHCND/stations/GHCND:USW00094846/detail) and then select the "VIEW DATA" button, then the bottom of the report describes some of the symbols you might see, and also has some column information:

* "s": This data value failed on of NCDC's quality control tests.
* "T": values in the Precipitation category above indicate a TRACE value was recorded.
* "A": values in the Precipitation Flag or the Snow Flag column indicate a multiday total, accumlated since last measurement, is being used.
* The 24 Hour Precipitation Category has multiple sub-categories, "Rain, melted snow, etc. (in)", "Snow, ice pellets, hail (in)", and "Snow, ice pellets, hail, ice on ground (in)".

Very disappointing "documentation" can be found [here](http://www1.ncdc.noaa.gov/pub/data/cdo/documentation/PRECIP_HLY_documentation.pdf).

I'm pretty sure the hourly precipitation amount has already been transformed to the rainfall equivalent. If you look at the "snowpocalypse" on Feb 1 2011, there was 13.6 inches of snow total, and > 20 inches total on Feb 1 2011 and Feb 2 2011. The hourly precipitation summed to the daily amount reports < 1 inch for both days.
