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

The literature shows image analysis of rock thin sections studying small fields of view and targeting mineral grains with one microscopy is a challenging task. Large-scale (and correlative) microscopy requires a step evolution of image analysis software and algorithms that can cope with image pyramids for registration, segmentation, classification, and image representation of pixels and objects that simplify observation of the underlying data. The average user will need centralised orchestration of data management, image processing, and image analysis for trialling and interacting with open-source code and data that might not be locally available (the cloud).  

This workshop will introduce offline standalone software to process very large images: (1) Cube converter, (2) Chemistry simplifier, and (3) phase interpreter. They can be combined into image analysis pipelines for semi-automated mineralogy. The pipelines can be customised by the user and work on their PC to allow advanced navigation, pixel classification (QuPath software), object identification and dimensionality reduction applied to a variety of rock types (igneous, metamorphic, and sedimentary). Using an example of a websterite thin section, the workshop will also demonstrate how image analysis tools can help to transition from subjective user-driven classification to more objective interpretation of object classes and their mutual relationships. 


### Material: 

All the workshop material is digital and freely distributable (see [all data folder]()). For those who experience difficulties downloading all the data, you can copy you the files directly from SSD external drives. A more granular description (and links) to the componet datasets is given below:

 - Booklet to follow the workshop: [booklet_11-Nov-25.pdf](https://drive.google.com/file/d/1xA68dYMQDb1VaDo7Cq8QewV1nsKaYx2e/view?usp=sharing).      
 - Part 1 dataset: Navigating in QuPath ([registered_pyramids](https://drive.google.com/file/d/17HUjqnrstj973W0yZ2to8ISFQDCgzAhG/view?usp=sharing))
 - Part 2 dataset: Petrographic image analysis ([optical](https://drive.google.com/file/d/1alYwxB4FVPrAXSYkgTcJ7XCslXdlUN-S/view?usp=sharing) and [sem](https://drive.google.com/file/d/1dq-D8QRIPvjWUDy57zgbDAL1bwYE_daw/view?usp=sharing))
    - 2A for Windows users: Ray tracing and dimensionality reduction
    - 2B for Mac users: Pixel-based image segmentation ([registered_pyramids](https://drive.google.com/file/d/17HUjqnrstj973W0yZ2to8ISFQDCgzAhG/view?usp=sharing))
 - Extra learning material [booklet_11-Nov-24_extra materials.docx](https://docs.google.com/document/d/16Oe7utO8dU0GDCi39jahrS_OdX93hFCM/edit?usp=sharing&ouid=104458834416513766328&rtpof=true&sd=true) containing:
    - Courses and resources to learn image analysis
    - Video links on image analysis routines (e.g., image registration)
 - Video on VS200 slide scanner acquisition     
 - The required installers of the internal and external software are provided in the [files](https://drive.google.com/file/d/1fIeNmyiiVdQnmyWdt_jkFgN5HZlntpu8/view?usp=sharing) folder. 
 
For the internal (new) software, the **executables** can also be found in the [files](https://drive.google.com/file/d/1fIeNmyiiVdQnmyWdt_jkFgN5HZlntpu8/view?usp=sharing) folder (run in Windows 11):
 - Cube converter: processing optical images
 - Chemistry simplifier: processing chemical images
 - Phase interpreter: producing mineral phase maps

All packages are in version 1 (beta). For developers, the GitHub source code can be found at:
 - [Cube converter repo](https://github.com/marcoaaz/cube_converter): in Python language
 - [Chemistry simplifier repo](https://github.com/marcoaaz/chemistry_simplifier): in Python 
 - [Phase interpreter repo](https://github.com/marcoaaz/phase_interpreter): in MatLab

For the external software*, it can also be downloaded from:
  - QuPath [website](https://qupath.github.io/)
  - ImageJ-[Fiji](https://imagej.net/software/fiji/downloads): for image alignment/registration
   - After opening for the first time, update the plugins going to ‘Top menu > Help > Update.. > Apply Changes’. Restart Imagej after that.
   - Normally, you should have ‘ImageJ > Plugins > BigDataViewer > BigWarp’ available
  - [IrfanView](https://www.irfanview.com/): optional for opening images

*If the installers (for Windows 11) are not compatible with your PC.

### Workflow

The overall workflow below shows the type of microscopy data and how it will flow between the software packages and give you an idea of your progress. Remember that all data management and software interactions are done manually.

Microscopy techniques, workflow steps, and software packages involvement (green= chemistry simplifier; blue= cube converter; orange= phase interpreter):

![Workflow placeholder](/images/Workflow_v2-01.png "Workflow")


Get ready to make discoveries and build/imagine new tools. Citing our work (references in GitHub) will make us more sustainable. 


Cheers,  
Marco



