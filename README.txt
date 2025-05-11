#############################################################################################################################

This project develops a habitat suitability model for the Northern Goshawk in British Columbia's Lillooet River Valley, 
integrating LiDAR-derived forest structure data with environmental variables through MaxEnt modelling. The analysis produces 
spatially-explicit habitat suitability maps that classify areas into suitability levels, informing sustainable forest 
management practices and conservation planning for this forest-dependent raptor.

#############################################################################################################################

This project was created by Ryan Milia as part of the Geospatial Data Analytics Program at the Centre of 
Geographic Sciences, Nova Scotia Community College, Lawrencetown, Nova Scotia. It is intended for educational 
purposes only. All content is unedited and unverified. © 2025 COGS

#############################################################################################################################

LiDAR point cloud data was provided by Tsetspa7 Forestry. All environmental layers were derived from 
the "Veg_Comp_LYR_L1_POLY_2023" VRI layer, collected from the British Columbia Open Data Portal. The 
"Freshwater Atlas" layer was collected from the BC Geographic Data Services and used to mask water 
bodies in the habitat suitability models. LiDAR data was excluded due to large file size.
	
#############################################################################################################################

Instructions:
	1. Download data from this link: "https://github.com/ryanjamesmilia/tsetspa7_habitat_model/releases/tag/v1".
	2. Extract "tsetspa7_v2.zip" to preferred location.
	3. Install the following packages, if required: caret, dismo, dplyr, ggplot2, maxnet, pROC, raster, and sf.
	4. Open and run the markdown notebook in RStudio: "tsetspa7_model_v2.Rmd".

#############################################################################################################################

Project Directory:
1. documents/
   - tsetspa7_final_report.pdf: final report.
   - tsetspa7_v2.Rmd - R Mardown notebook containing MaxEnt habitat suitability model.
   - tsetspa7_notes.docx: detailed project notes.
2. maps/
   - tsetspa7_3-Level.pdf: 3-Level habitat suitability map.
   - tsetspa7_5-Level.pdf: 5-Level habitat suitability map.
3. tsetspa7_v2/
   - Data folder supporting R Markdown notebook
-----------------------------------------------------------------------------------------------------------------------------
