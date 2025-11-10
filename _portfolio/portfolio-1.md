---
title: "SGGMP 2025: Image analysis workshop"
excerpt: "Data and new software will be required at https://www.sggmp25.com/ to run the image analysis workshop. This page contains the software required to complete the exercises during the workshop<br/><img src='/images/Workflow_v2-01.png'>"
collection: portfolio
---

## Image analysis workshop

Speakers: 
 - Prof. Balz Kamber: introduction
 - Dr. Marco Acevedo Zamora: exercises

All the workshop material is digital and freely distributable [folder](). For those who experience difficulties downloading all the data, some colleagues can copy you the files with SSD external drives. The description and links to the specific datasets are given below.

The required material, data and external software are:
 - Guidelines for the seminar: [booklet_11-Nov-25.pdf](). 
 - QuPath v0.6 [installer]: Bioinformatics software for whole-slide image analysis ([Bankhead et al., 2017](https://pubmed.ncbi.nlm.nih.gov/29203879/))       
 - [Part 1](): Navigating in QuPath
 - Part 2:
    - Windows users, [Part 2](): Ray tracing and dimensionality reduction
    - Mac users, [Part 2](): Pixel-based image segmentation
 - Extra material:
    - [Part 3](): Videos on image registration and Phase interpreter software
    - [Part 4](): Courses and resources on modern image analysis
 
 - Installers can also be downloaded from:
  - QuPath [website](https://qupath.github.io/)
  - Optional: 
    - ImageJ-[Fiji](https://imagej.net/software/fiji/downloads): for image registration
    - [IrfanView](https://www.irfanview.com/): for opening images

The image analysis software **executables** can be found at (only run in Windows 11):
 - [Cube converter]()
 - [Chemistry simplifier]()
 - [Phase interpreter]()

All software are in version 1 (beta) and this is a first time release. If you wish to have the source code, fork and contribute to improve the software, the repositories are in GitHub:
 - [Cube converter repo](https://github.com/marcoaaz/cube_converter)
 - [Chemistry simplifier repo](https://github.com/marcoaaz/chemistry_simplifier)
 - [Phase interpreter repo](https://github.com/marcoaaz/phase_interpreter)


### Workflow

The overall workflow below shows the type of microscopy data and how it will flow between the software packages and give you an idea of your progress:

Microscopy techniques and steps:

<img width=90% height=90% alt="Image" src='/images/Workflow_v2_no outlines-01.png'>

Application of software packages (green= chemistry simplifier; blue= cube converter; orange= phase interpreter):

<img width=90% height=90% alt="Image" src='/images/Workflow_v2-01.png'>

Remember that all data management and software interactions are done manually. 

If you liked the seminar, the best support is to cite our scientific work and to collaborate with us for making discoveries and building new tools. Thank you.

Cheers,  
Marco



