![monocle_logo](https://monocle-h2020.eu/getattachment/Resources/MONOCLE_LOGO_-_Grey_with_text_-_2000px.png)


# MONOCLE LOW COST SENSOR SUPPORT PACKAGE
D2.5 Support package for MONOCLE Low Cost Sensors

# What is Monocle?

Funded by EU H2020 MONOCLE brings together 12 partners from across Europe to create sustainable in situ observation solutions for Earth Observation (EO) of optical water quality in inland and transitional waters.


# About this repository


Here you will find software and documentation for our low cost sensors (iSPEX, kDUINO, Fresh Water Watch)


## Introduction
This readme acts as a reference for the Low Cost Sensor support software and / or documentation. Both software and documentation are still into development, so
the contents of this file can and will change.


## SPECTACLE / iSPEX

### General description
The spectacle app, scripts and back end are used for smartphone camera calibrations and captures RAW image sensor data along with positional data. The software (both iOS and Android) is a starting point for building the iSPEX (a smartphone spectropolarimater) app.


### Repositories
iSPEX 2 repository (Python)
https://github.com/burggraaff/ispex2

### Description 
Data reduction scripts in python, takes raw image and metadata from SPECTACLE app/DB.


SPECTACLE Repository (Python)
https://github.com/monocle-h2020/camera_calibration

SPECTACLE App
### Decription
iOS and Android calibration apps (xcode and android studio development resources). 



IOS
https://github.com/monocle-h2020/spectacle_ios

Android
https://github.com/monocle-h2020/spectacle_android


###
Mobile back end. Used for storage, metadata, push notifications, offline sync.

SPECTACLE/iSPEX Back end database dump
https://github.com/monocle-h2020/spectacle_db


### Support scripts 


## KDUINO/KSTICK





- KduPro code
https://github.com/Carlos-Rodero/KdUINO_Feather?organization=Carlos-Rodero&organization=Carlos-Rodero

 Data analysis codes 
https://git.csic.es/36579996Z/kduino-data-analysis 


## DRONES

https://www.dji.com/nl/ground-station-pro

 Sitemark created guidelines the correctly use the DJI GSPro drone pilot app for data collection over water. This app works on ios systems. The flight guidelines are referenced here: https://github.com/monocle-h2020/low_cost_sensor_support_package/blob/master/Monocle%20Flight%20Guidelinesv12020704_update.pdf
To support drone pilots in their flight mission planning, Sitemark  created a website (called MONOCLE Flight Planner) to help define coordinates for the drone to hover in order to capture a certain buoy and in function of the position of the sun.

https://sm-projects-monocle.azurewebsites.net/



## FRESH WATER WATCH




FWW methods URL :https://freshwaterwatch.thewaterhub.org/content/your-test-kit
FWW methods document: https://freshwaterwatch.thewaterhub.org/sites/default/files/fww-methods-manual.pdf
 
FWW health and safety document: https://freshwaterwatch.thewaterhub.org/sites/default/files/health-and-safety-manual.pdf
 
FWW site selection info: https://freshwaterwatch.thewaterhub.org/content/where-test
 
FWW data upload instructions: https://freshwaterwatch.thewaterhub.org/content/uploading-results
 
FWW Geoserver URL for earthwatch is: https://geo.earthwatch.org.uk/

# FUNDING

![EU_logo](https://ec.europa.eu/easme/sites/easme-site/files/euflag.png)

This project has received funding from the European Union’s Horizon 2020 research and innovation programme under grant agreement No 776480


# LICENSE


