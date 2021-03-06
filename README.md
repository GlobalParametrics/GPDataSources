# GPDataSources
An overview of data sources used by Global Parametrics for index development

## GP Data Classes
GP maintains a repository of climatology, forecast, and extreme event data that is useful for assessing risk from geophysical phenomena.  These datasets are broadly characterized in the following data classes:
- Weather (WX)
- Tropical Cyclone (TC)
- Earthquake (EQ)
- Exposure (EX)
- Physical Properties (PP)

## GP Data Collection
GP generates datasets using propritetary algorithms and maintains a repository of publicly available data.  GP harmonizes each dataset to have consistent datetime and variable conventions, lowering the barrier to comparisons between disparate models. 

Public datasets that GP maintains include:

- [CFSR](https://climatedataguide.ucar.edu/climate-data/climate-forecast-system-reanalysis-cfsr) (WX): Global climate reanalysis generated by NCEP/NCAR. Covers the time period from 1/1979-3/2011. Sub-daily data.
- [CFSv2](http://cfs.ncep.noaa.gov/) (WX): Operational global climate forecast model generated by NCEP/NCAR and distributed by NOAA.  Covers the time period from 3/2011 - Present. Sub-daily data.
- [GFS](https://www.ncdc.noaa.gov/data-access/model-data/model-datasets/global-forcast-system-gfs)<sup>[1](#footnote_1)</sup> (WX): Operational global weather forecast  model generated by NCEP/NCAR and distributed by NOAA. Covers the time period from 3/2004 to Present. Sub-daily data.
- [JRA55](http://ds.data.jma.go.jp/gmd/jra/atlas/en/index.html) (WX): Global climate reanalysis generated by the Japanese Meteorological Agency (JMA). Covers the time period from 1958 to 2016. Sub-daily data.
- [CHIRPS](http://chg.geog.ucsb.edu/data/chirps/)<sup>[1](#footnote_1)</sup> (WX): Near realtime global precipitation dataset generated by the Climate Hazards Group. Covers the time period from 1981 to Present. Daily data.
- [GPCC](https://www.dwd.de/EN/ourservices/gpcc/gpcc.html) (WX): Global precipitation dataset generated by the Global Precipitation Climatology Centre (GPCC).  Covers the time period from 1891 to Present. Monthly data.
- [ESA-CCI](https://www.esa-soilmoisture-cci.org/)<sup>[1](#footnote_1)</sup> (WX): Global soil moisture dataset generated by the European Space Agency.  Covers the time period from 1978 to 2018. Daily data.
- [TRMM](https://pmm.nasa.gov/TRMM) (WX): Global precipitation dataset generated by NASA. Covers the time period from 3/2000 to 4/2015.
- [GPM](https://pmm.nasa.gov/GPM) (WX): Global precipitation dataset generated by NASA. Covers the time period from 3/2014 to Present.
- [GSOD](https://data.nodc.noaa.gov/cgi-bin/iso?id=gov.noaa.ncdc:C00516)<sup>[1](#footnote_1)</sup> (WX): Global Summary of the Day is weather station dataset maintained by NOAA and the WMO.  Covers a variable time period from 1929 to Present, with data from 1973 to Present being the most complete.
- [Geonames](https://www.geonames.org/about.html) (EX,PP): Geographical database of all countries
- [OpenStreetMap](https://www.openstreetmap.org/about)<sup>[2](#footnote_2)</sup> (EX,PP): Geographical database of all countries
- [IBTrACS](https://www.ncdc.noaa.gov/ibtracs/) (TC): Global database of historical tropical cyclone tracks generated by NOAA
- [Centennial EQ Catalog](https://earthquake.usgs.gov/data/centennial/) (EQ): Global database of historical earthquakes generated by USGS
- [ISC-GEM EQ Catalog](http://www.isc.ac.uk/iscgem/) (EQ): Global database of historical earthquakes generated by ISC-GEM
- [MODIS](https://modis.gsfc.nasa.gov/)<sup>[1](#footnote_1)</sup> (PP): Global remote sensed landcover database generated by NASA.
- [GFSAD30](https://www.usgs.gov/centers/wgsc/science/global-food-security-support-analysis-data-30-m)<sup>[1](#footnote_1)</sup> (PP): Global remote sensed cropland  database generated by NASA and USGS.
- [GPW](http://sedac.ciesin.columbia.edu/data/collection/gpw-v4)<sup>[2](#footnote_2)</sup> (EX): Global population dataset generated by NASA
- [GEBCO](https://www.gebco.net/)<sup>[2](#footnote_2)</sup> (PP): Global bathymetry dataset generated by IHO and IOC and distributed by the British Oceanographic Data Center
- [ETOPO1](https://www.ngdc.noaa.gov/mgg/global/global.html)<sup>[2](#footnote_2)</sup> (PP): Global integrated digital elevation and bathymetry model developed by NOAA.
- [SRTM](https://www2.jpl.nasa.gov/srtm/index.html)<sup>[1](#footnote_1)</sup> (PP): Global digital elevation model developed by NASA.
- [GAEZ](http://www.fao.org/nr/gaez/en/)<sup>[2](#footnote_2)</sup> (PP): Global Agro-Ecological Zones model developed by the Food and Agriculture Organization of the United Nations (FAO) and the International Institute for Applied Systems Analysis (IIASA).

Open datasets that GP generates include:

- [MPAS](https://mpas-dev.github.io/)<sup>[1](#footnote_1)</sup> (WX): Global climate forecast model developed by NCAR and implemented by Enki Research and Global Parametrics. Covers the time period from 1960 to Present. Daily data.
- [WRF-ARW](https://www.mmm.ucar.edu/weather-research-and-forecasting-model)<sup>[1](#footnote_1)</sup> (WX): Global climate forecast model developed by NCAR, NCEP, and AFWA and implemented by Enki Research and Global Parametrics. Covers the time period from 1960 to Present. Daily data.
- Fea (TC): Parametric tropical cyclone hazard (wind, precipitation, storm surge, wave), damage, and economic loss models developed by Enki Research and implemented by Global Parametrics.
- [GA-TCRM](https://geoscienceaustralia.github.io/tcrm/docs/intro.html)<sup>[2](#footnote_2)</sup><sup>[3](#footnote_3)</sup> (TC): Parametric tropical cyclone track generation and hazard (wind, precipitation, storm surge, wave) models developed by Geoscience Australia and implemented by Global Parametrics.
- Beria (EQ): Parametric earthquake hazard (pga), damage, and economic loss models developed by Enki Research and implemented by Global Parametrics.
 - [GEM-OQ](https://www.globalquakemodel.org/)<sup>[2](#footnote_2)</sup><sup>[3](#footnote_3)</sup> (EQ): Parametric earthquake hazard (pga, sa) model developed by the Global Earthquake Model and implemented by Global Parametrics.
- Macha (EX): Global exposure dataset for risk modeling developed by Enki Research and implemented by Global Parametrics.
- Lachesis (EX): Global high-resolution exposure dataset developed by Enki Research and implemented by Global Parametrics.

<sub><a name="footnote_1">1</a>: Archival data available, database under development</sub>  
<sub><a name="footnote_2">2</a>: Archival data and database under development</sub>  
<sub><a name="footnote_3">3</a>: Available for select regions</sub>  
