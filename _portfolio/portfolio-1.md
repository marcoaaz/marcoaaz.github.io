---
title: "SGGMP 2025: Image analysis workshop"
excerpt: "Data and new software will be required at [https://www.sggmp25.com/](https://www.sggmp25.com/) to participate in the image analysis workshop. This webpage contains the software required to complete the exercises during the workshop<br/><img src='/images/Workflow_v2-01.png'>"
collection: portfolio
---

## Image analysis workshop

Welcome. This webpage explains the workshop and provides the data required to run it in your PC.

### Presenters: 

 - Dr. Marco A. Acevedo Zamora: second introduction and exercises
 - Prof. Balz S. Kamber: first introduction


### Introduction:

The petrographic polarising microscope is a foundational tool in geoscience research to answer first-order questions such as rock micro-structure, fabric, and mineral assemblage at multiple observation scales. The arrival of fast and reliable optical slide scanners for biomedical imaging has motivated their re-implementation as polarising microscopes for imaging rock thin sections. Investigators are now demanding sharing their slide data around the world via virtual microscopes, scaling up image analysis to hundreds of thin sections, and integrating optical imagery with other modalities, especially chemical maps.  

This requires image analysis software and algorithms that can cope with image pyramids for registration, segmentation, classification, and image representation of pixels and objects that simplify observation of the underlying data. For large-scale correlative microscopy, the average user will need centralised orchestration of data management, image processing, and image analysis for trialling and interacting with open-source code and data that might not be locally available (the cloud).  

This presentation will give examples of image analysis pipelines that work on a powerful PC for navigation, pixel classification, object identification and dimensionality reduction applied to a variety of rock types (igneous, metamorphic, and sedimentary). It will also demonstrate how image analysis tools can help to transition from subjective user-driven classification to more objective interpretation of object classes and their mutual relationships. 


### Material: 

All the workshop material is digital and freely distributable [folder](). For those who experience difficulties downloading all the data, some colleagues can copy you the files with SSD external drives. The description and links to the specific datasets are given below.

The required data and external software are:
 - Booklet to follow the workshop: [booklet_11-Nov-25.pdf](). 
 - QuPath v0.6 [installer]: Bioinformatics software for whole-slide image analysis ([Bankhead et al., 2017](https://pubmed.ncbi.nlm.nih.gov/29203879/))       
 - [Part 1](): Navigating in QuPath
 - Part 2:
    - [Part 2](), Windows users: Ray tracing and dimensionality reduction
    - [Part 2](), Mac users: Pixel-based image segmentation
 - Extra learning material:
    - [Part 3](): Videos on image registration and Phase interpreter software
    - [Part 4](): Courses and resources to learn image analysis
 
 - External software will be required. The installers can also be downloaded from:
  - QuPath [website](https://qupath.github.io/)
  - ImageJ-[Fiji](https://imagej.net/software/fiji/downloads): for image alignment/registration
   - After opening for the first time, update the plugins going to ‘Top menu > Help > Update.. > Apply Changes’. Restart Imagej after that.
   - Normally, you should have ‘ImageJ > Plugins > BigDataViewer > BigWarp’ available
  - [IrfanView](https://www.irfanview.com/): optional for opening images

The internal software **executables** can be found at (only run in Windows 11):
 - [Cube converter](): processing optical images
 - [Chemistry simplifier](): processing chemical images
 - [Phase interpreter](): producing mineral phase maps

All software are in version 1 (beta) and this is a first time release. If you wish to have the source code, fork and contribute to improve the software, the repositories are in GitHub:
 - [Cube converter repo](https://github.com/marcoaaz/cube_converter): in Python language
 - [Chemistry simplifier repo](https://github.com/marcoaaz/chemistry_simplifier): in Python 
 - [Phase interpreter repo](https://github.com/marcoaaz/phase_interpreter): in MatLab


### Workflow

The overall workflow below shows the type of microscopy data and how it will flow between the software packages and give you an idea of your progress. Remember that all data management and software interactions are done manually.

Microscopy techniques, workflow steps, and software packages involvement (green= chemistry simplifier; blue= cube converter; orange= phase interpreter):

![Workflow placeholder](/images/Workflow_v2-01.png "Workflow")


If wanting to see more from our research group, the best support is citing our scientific work and propose interinstitutional/international collaboration. Get ready to make discoveries and build/imagine new tools. 


Cheers,  
Marco



