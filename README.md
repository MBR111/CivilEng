# CivilEng. Qgis provider for Civil Engineering tools
Version=0.1

Author=Iñigo Marin

email=proy.mbr.gmail.com


Tools to automate the early design of civil engineering projects. This is a Qgis provider with two tools: Reservoir and Earthworks.
# Reservoir:
Based on and existing terrain DEM (raster file), the dam axis location (line or polygon vector layer), the top of dam level, the depth from the top of the dam to the water surface, and providing a point upstream of the dam, inside the reservoir, the plugin returns a modifed DEM raster file with the existing terrain modified with the dam, and a water depth raster file of the flooded area (as result of running r.lake). 

# Earthworks: 
Based on and existing terrain DEM (raster file), a platform design (line or polygon vector layer), the platform base level, and the cut and fill slopes, the plugin returns a modifed DEM raster file with the earthwork.
