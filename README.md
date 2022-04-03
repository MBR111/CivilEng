# CivilEng. Qgis provider for Civil Engineering tools
Version=0.1

Author=Iñigo Marin

email=proy.mbr.gmail.com


Tools to automate the early design of civil engineering projects. This is a Qgis provider with three tools: Reservoir, Earthworks and LRS.

# Reservoir:
Based on and existing terrain DEM (raster file), the dam crest axis location (line or polygon vector layer), the top of dam level, the depth from the top of the dam to the water surface, the dam wall slope, and providing a point upstream of the dam, inside the reservoir, the plugin returns a modifed DEM raster file with the existing terrain modified with the dam, and a water depth raster file of the flooded area (as result of running r.lake). 


![Reservoir Sample image](/support/Reservoir_sample_image.png)

The initial required data is presented graphically in the following image as well as the results for a test sites:

![Reservoir Sample image](/support/Reservoir2.JPG)

# Earthworks: 
Based on and existing terrain DEM (raster file), a platform design (line or polygon vector layer), the platform constant base level, and the cut and fill slopes, the plugin returns a modifed DEM raster file with the earthwork.

In the two attached images the initial data and the result of the process are presented for a test site.

![Earthworks Sample image](/support/Trench4.JPG)


![Earthworks Sample image](/support/Trench3.JPG)


Another images of different tests can be seen below.

![Earthworks Sample image](/support/Trench.JPG)

![Earthworks Sample image](/support/Pile2.JPG)

![Earthworks Sample image](/support/Sink.JPG)


# LRS:
Based on and existing polyline (vector file), the linear referencing marks and text are created for each 25 and 100 m intervals.

![LRS Sample image](/support/LRS_sample_image.png)
