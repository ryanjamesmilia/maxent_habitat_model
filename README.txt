###########################################################################################################################

This project develops a habitat suitability model for the Northern Goshawk in British Columbia's Lillooet River Valley, 
integrating LiDAR-derived forest structure data with environmental variables through MaxEnt modelling, with a second model 
incorporating synthetic occurrence points to address limited data availability. The analysis produces spatially-explicit 
habitat suitability maps that classify areas into suitability levels, informing sustainable forest management practices 
and conservation planning for this forest-dependent raptor.

###########################################################################################################################

This project was created by Ryan Milia as part of the Geospatial Data Analytics Program at the Centre of 
Geographic Sciences, Nova Scotia Community College, Lawrencetown, Nova Scotia. It is intended for educational 
purposes only. All content is unedited and unverified. © 2025 COGS

###########################################################################################################################

LiDAR point cloud data was provided by Tsetspa7 Forestry. All environmental layers were derived from 
the "Veg_Comp_LYR_L1_POLY_2023" VRI layer, collected from the British Columbia Open Data Portal. The 
"Freshwater Atlas" layer was collected from the BC Geographic Data Services and used to mask water 
bodies in the habitat suitability models. LiDAR data was excluded due to large file size.
	
###########################################################################################################################

Instructions:
	1. Download data from this link: 
	2. Extract "tsetspa7.zip" to preferred location.
	3. Install the following packages, if required: caret, dismo, dplyr, ggplot2, maxnet, pROC, raster, sf, sp, and MASS.
	4. Open and run the following markdown notebooks in RStudio:
       	- "tsetspa7_model.Rmd" (original MaxEnt model)
       	- "tsetspa7_synthetic_model.Rmd" (synthetic MaxEnt model)

###########################################################################################################################

Project Directory:
1. maps/
   - Habitat suitability maps
2. notebooks/
   - tsetspa7_model.Rmd - R Markdown notebook for the original MaxEnt model
   - tsetspa7_synthetic_model.Rmd - R Markdown notebook with additional synthetic data
3. tsetspa7/
   - Data folder supporting R Markdown notebooks
---------------------------------------------------------------------------------------------------------------------------
