# Solar-SSSI
Jupyter notebook for mapping planning applications of solar farms in nature reserves (SSSIs)

Data source is planning applications from https://www.planit.org.uk/api/ 
Considers filters for solar farm planning applications in dataframe.
Looks at limitations in data of spatial geometries.
Takes SSSI shapefile from https://environment.data.gov.uk/DefraDataDownload/?mapService=NE/SitesOfSpecialScientificInterestEngland&Mode=spatial
Maps planning applications within SSSIs in leafmap.

TODO: refine API filters, consider postGIS datasource, apply buffers (e.g. 1km) to POINTS of planning applications
