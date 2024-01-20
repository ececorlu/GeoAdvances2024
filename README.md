# GeoAdvances2024
##  Visibility Analyses using BIM-GIS Integration

The documents of the article "Visibility Analyses using BIM-GIS Integration"
In this article, in BIM GIS information is modeled. Then visibility analysis is done. The files are located in this repository.

Revit files are used as BIM software. [.rvt] is the extension of this software.  In Revit, Dynamo is a visual programming software allowing users to write code using nodes. [.dyn] is the extension of this software. In Revit, elements are defined as family, then this family can downloaded in different Revit files as an object. Family is created in .rfa extension. In this article, trees are created from the [Tree.rfa] family. OSM files provide cadastral data and are used in to create GIS in Revit using Dynamo. [.osm] is the extension of this file. Topography is created from USGS SRTM Data, which has tiff extension.
<br />

**To create the document files from scratch**

You need to create 3 different rvt file, since cadastral data is divided into 3 to reduce file sizes. OSM 1 is main research area, osm 2 and 3 are areas located near the research area. Each is created separately then using buildins move files according to their exact location.

To create each revit file

1- Eyup_maim.rvt file is the template of BIM file. research area 1 can be created from this file. Eyup_template.rvt file is the template of osm2 and osm 3 files. research area 2 and 3 can be created on this file.  

2- To create GIS in BIM run osm.dyn file in BIM visual programming. the cadastral data information is gathered from the OSM file, topography is created from tiff file. To create each file osm file needed to be changed. 

3- After creating the files, files are combined using buildings. osm2 and osm 3 has Eyup wedding building, and osm 1 and osm 2 has one same building. the files are moved to match this buildings location. 

4- visual analysis is done using "Eyup_visual openness indexes.dyn" file in the combined Revit file. 

5- A person located in the front facade 2. elevation is chosen as an observer. And the view distances are chosen first 50 m and then 150 m in the article.

6- A person located in the front facade 4. elevation is chosen as an observer. And the view distances are chosen first 50 m and then 150 m in the article.

7- A person located in the rear facade 2. elevation is chosen as an observer. And the view distances are chosen first 50 m and then 150 m in the article.

8- A person located in the rear facade 4. elevation is chosen as an observer. And the view distances are chosen first 50 m and then 150 m in the article.

**To reach the final model use the link below.**

https://drive.google.com/file/d/1pF4S1SGk7Z_zntAAqtv44gE5OTMOCgtq/view?usp=sharing

<br />


**TL;DR**
***

The article abstract is written below.

ABSTRACT: 

Visibility is a significant parameter for defining, developing, and evaluating space in the AEC (Architecture, Engineering, and Construction) Industry. Therefore, visibility is considered when designing visually comfortable buildings. Visibility is also a significant parameter in building appraisal.  Therefore, in this study, visibility was examined through 3-dimensional (3D) isovists, which are thought to represent the human perception of vision. Visibility was examined regarding spatial openness and mathematically calculated “visual openness indexes” were developed for building valuation. The analysis area was selected in Istanbul, and the urban model was created by using Geographic Information System (GIS) data in Building Information Modelling (BIM) software.  Due to, economic reasons affecting different stakeholders in building valuation, it is necessary to create an accurate urban model. For this reason, in the study, the process of obtaining current and accurate GIS data covering the world from open sources is preferred. Then, the process of correctly transferring GIS data to BIM is explained. A sufficient urban model for analysis is created. To calculate the openness indexes, the dormitory in the Golden Horn was modeled in BIM, and different rooms' openness indexes were calculated. Some solutions have been presented to ensure the modeling process with large file sizes and in the calculation of visibility factors. To allow different AEC stakeholders to calculate these indexes, modeling, and calculation is done within BIM. Eventually, it was calculated how much the building users cognitively perceive the openness of the view, and a mathematical comparison of the different rooms' openness indexes was provided.

KEYWORDS: Visibility, BIM-GIS Integration, 3D Isovists, Line of Sight Analysis, Visual Openness, Building Appraisal (Valuation)
