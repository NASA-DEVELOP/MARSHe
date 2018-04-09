===============
 Marsh Remote Sensing Health Evaluation (MaRSHE)
===============

Date Created: July 3, 2017

These scripts allow the user to display selected Landsat and Sentinel imagery and apply analyses and/or classification to a specific image or collection of images. 

The first script performs an unsupervised classification to determine the extent of marsh wetlands. The script calculates current Marsh wetland extent for our study area and future coding will achieve different year' marsh extent for comparison purposes as well as exporting marsh extent for change detection purposes.  Statistics about changes will also be a future component.

The second script calculates changes in NDVI from a chosen ten year reference period. The user is able to determine both positive and negative NDVI change within a study area for a different period. This script calls the average NDVI from 1984 to 1995 and then maps the deviation from that average for the period of 1996 to 2017. Once changes are determined and mapped, specific, user-determined points can be graphed out with the included code to create charts. Future coding hopes to achieve exported gain and loss maps and additional statistics.

In the future, once the marsh extent maps have been created for several years, these maps will be exported and will be used as Marsh extent masks for the NDVI anomaly script (and the scripts will be combined for simplicity).        

 Required Packages
===================
* Google Earth Engine 
* 
* Two Scripts (for now - will be combined in future)
* 1) Wetland_Classification_DEVELOP (2017Sum_GSFC_ChesapeakeBayEco_DraftCode1)
* 2) CB_NDVI_anomoly_DEVELOP_DL (2017Sum_GSFC_ChesapeakeBayEco_DraftCode2)


 Parameters
-------------

1. Register for a Google Earth Engine developer account
2. Each script has some manual inputs and selections
3. Each script will generate different outputs in the form of graphs, maps, and statistics.

 Contact
---------
Name(s): John Fitz
E-mail(s): johnfitz058@gmail.com , john.m.fitz@nasa.gov


***
This is just a basic template of the metadata and steps that we would
like to have in a README file (name of code, packages and other dependencies,
steps necessary to run the code, and a point of contact). Feel free to add 
more content as necessary so a future DEVELOPer can understand your code. 
***
