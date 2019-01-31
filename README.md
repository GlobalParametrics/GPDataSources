# GPDataSources
An overview of data sources used by Global Parametrics for index development

## GP Data Classes
GP maintains a repository of climatology, forecast, and extreme event data that is useful for assessing risk from geophysical phenomena.  These datasets are broadly characterized with the following nomenclature:
- Weather (WX)
- Tropical Cyclone (TC)
- Earthquake (EQ)

## GP Data Collection
GP generates datasets using propritetary algorithms and maintains a repository of publicly available data.  GP harmonizes each dataset to have consistent datetime and variable conventions, lowering the barrier to comparisons between disparate models. 

Public datasets that GP maintains include:

- [CFSR](https://climatedataguide.ucar.edu/climate-data/climate-forecast-system-reanalysis-cfsr): Global climate reanalysis generated by NCEP/NCAR. Covers the time period from 1/1979-3/2011. Sub-daily data.
- [CFSv2](http://cfs.ncep.noaa.gov/): Operational global climate forecast model generated by NCEP/NCAR and distributed by NOAA.  Covers the time period from 3/2011 - Present. Sub-daily data.
- [GFS](https://www.ncdc.noaa.gov/data-access/model-data/model-datasets/global-forcast-system-gfs): Operational global weather forecast  model generated by NCEP/NCAR and distributed by NOAA. Covers the time period from 3/2004 to Present. Sub-daily data.
- [JRA55](http://ds.data.jma.go.jp/gmd/jra/atlas/en/index.html): Global climate reanalysis generated by the Japanese Meteorological Agency (JMA). Covers the time period from 1958 to 2016. Sub-daily data.
- [CHIRPS](http://chg.geog.ucsb.edu/data/chirps/): Near realtime global precipitation dataset generated by the Climate Hazards Group. Covers the time period from 1981 to Present. Daily data.
- [GPCC](https://www.dwd.de/EN/ourservices/gpcc/gpcc.html): Global precipitation dataset generated by the Global Precipitation Climatology Centre (GPCC).  Covers the time period from 1891 to Present. Monthly data.
- [TRMM](https://pmm.nasa.gov/TRMM)v Global precipitation dataset generated by NASA. Covers the time period from 3/2000 to 4/2015.
- [GPM](https://pmm.nasa.gov/GPM): Global precipitation dataset generated by NASA. Covers the time period from 3/2014 to Present.
- [GSOD](https://data.nodc.noaa.gov/cgi-bin/iso?id=gov.noaa.ncdc:C00516): Global Summary of the Day is weather station dataset maintained by NOAA and the WMO.  Covers a variable time period from 1929 to Present, with data from 1973 to Present being the most complete.
- [Geonames](https://www.geonames.org/): Geographical database of all countries
- [IBTrACS](https://www.ncdc.noaa.gov/ibtracs/): Global database of historical tropical cyclone tracks generated by NOAA
- [Centennial EQ Catalog](https://earthquake.usgs.gov/data/centennial/): Global database of historical earthquakes generated by USGS
- [ISC-GEM EQ Catalog](http://www.isc.ac.uk/iscgem/): Global database of historical earthquakes generated by ISC-GEM

Proprietary datasets that GP maintains include:

- [MPAS](https://mpas-dev.github.io/): Global climate forecast model developed by NCAR and implemented by Enki Research and Global Parametrics. Covers the time period from 1960 to Present. Daily data.
- [WRF-ARW](https://www.mmm.ucar.edu/weather-research-and-forecasting-model): Global climate forecast model developed by NCAR, NCEP, and AFWA and implemented by Enki Research and Global Parametrics. Covers the time period from 1960 to Present. Daily data.
- Tropical Cyclone: Parametric tropical cyclone hazard and risk models developed by Enki Research and implemented by Global Parametrics.
- Earthquake: Parametric earthquake hazard and risk models developed by Enki Research and implemented by Global Parametrics.
- Exposure: Global dataset of gridded population and asset distribution
