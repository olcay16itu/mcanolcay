![ITU](https://github.com/olcay16itu/mcanolcay/blob/main/Readme%20images/it2_1.jpg)

 # GEO468E PERSONAL HOMEWORK

 ## Prepared by Mehmet Can Olçay 010160629
 
This github link contain my GEO468E Project.

# Aim of project

Determine the water and vegetation areas in study area which is İstanbul-Şile and detect vegetation difference between 2018 and 2020 years.NDVI used for the detect vegetation areas and ndwi used for the detect water bodies.

# Data Types(Inputs) of the project

Sentinel 2 images was used.Band3(GREEN) , band4(RED) and band8(NIR) used for project.

Sentinel 2 2020 Image : https://scihub.copernicus.eu/dhus/odata/v1/Products('5312f8e1-a70b-4597-9c2a-07be1b28c9bd

Sentinel 2 2018 Image ( Offline Image ) : https://scihub.copernicus.eu/dhus/odata/v1/Products('b0cc39b4-c94a-4f7c-bd37-4f97b7d49cee')/$value

# Workflow

Firstly , sentinel 2 images was downloaded from COPERNICUS.Then , opened in SNAP and used bands in project which determined on Data types exported.After,these exports was used in codes and output images used for analysis of water bodies and vegetation bodies.

# Which libraries used for this project ? 

Libraries added from coda software.

- rasterio
- matplotlib
- numpy

# What is NDVI ?

The normalized difference vegetation index (NDVI) is basically the ratio of radiation reflected from healthy vegetation to radiation reflected from all other sources and is calculated for the pixel in the image is marked.

![NDVI FORMULA](https://github.com/olcay16itu/mcanolcay/blob/main/Readme%20images/ndvi-formula.jpg)

# NDVI OUTPUTS

# NDVI 2016

![](https://github.com/olcay16itu/mcanolcay/blob/main/Readme%20images/ndvi2018.PNG)

# NDVI 2020

![](https://github.com/olcay16itu/mcanolcay/blob/main/Readme%20images/ndvi2020.PNG)
