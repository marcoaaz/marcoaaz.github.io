---
permalink: /
title: "Software tools for petrographic image analysis"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome. Hopefully you will find useful some of the software that I wrote and regularly use for analysing images during my latest research projects. They are free and open-source in order to be sustainable. Further updates that increase the number of options, reliability and performance will be driven by user feedback and my available resources. 

Everyone has something to contribute to build this expanding research field look forward to improve Petrography and Petrology applications. Try it in your own projects!


Latest updates (28-Apr-2026)
------

**Cube Converter** v1.2 works with optical microscopy data from rock thin sections imaged in slide scanners. The interface allows selecting VS200 polarising images in reflected and transmitted light and calculating mineral pleochroism and interference colours in all polariser orientations (available). The simplified image outputs are (maximum, minimum, stage rotation, mineral grains, and grain boundaries) provide a new level of understading in petrography and petrology of whole thin sections. Forward looking projects could make it compatible with other slide scanners and integrate petrographic microscopy and automated mineralogy. Future work involves polarised reflected light and cloud data management.

The latest version:
 - Uses cross-polarised light to calculate light wave modulation and grain boundaries images (e.g., 40'000 x 60'000 px) from many scans (6 images/modality) in ~50 minutes.
 - Is x2 faster and allows saving the outputs in another external drive (output folder) to reduce data friction (throttling). Preferably an SSD drive.

Here are the download links:  
 - Example pyroxenite: [link](https://sggmp25_workshop.fromsmash.com/vs200-example-pyroxenite) expires 28-May-26  
 - Windows OS executable: [link](https://zenodo.org/records/19689989)  
 - Code repository: [link](https://github.com/marcoaaz/cube_converter/tree/main)  

<img src='/images/cube_converter7.gif'>


**Chemistry Simplifier** v1.2 provides a new set of tools for having a first glance at your rock geochemical maps acquired in a geology laboratory with optical and electron microscopes. Although, it can be of general use (thin sections, pucks, satellite images, etc.)

The latest version:
 - Process dimensionality reduction representation images (PCA, DSA, and UMAP) two to three times faster than the previous version. So, you can process larger maps (e.g., 10'000x20'000 px) with many more layers (100 layers) in ~15 minutes.  
 - Align images with a reference image (e.g., aligning your chemical maps with optical maps of much higher spatial resolution) using non-rigid image registration.  
 - Has a simpler interface with sub-menus to configure the models.  
 - Allows 'contractive' denoising of the Neural network (Deep Sparse Autoencoder) image.  

Try it yourself with almost any dataset (and image format) as long as the input has the same image size. Keep sending your feedback to keep the project alive and.. do not forget to stop thinking about your data. Let your data speak for itself.

Here are the download links:  
 - Windows OS executable: [link](https://zenodo.org/records/19688702)
 - Code repository: [link](https://github.com/marcoaaz/chemistry_simplifier/tree/main)

<img src='/images/chemistry_simplifier.gif'>


Re-uploading Workshop material (29-Apr-26)
------

We ran a workshop (see Portfolio tab) to teach how to use the standalone software tools and reach a wider audience. The latest update of the seminar material has been uploaded to a data sharing service: [**link**](https://sggmp25_workshop.fromsmash.com/upload3-marco) (expiring 29-May-2026).



