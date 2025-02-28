# environmental-data-week3


NB: the /data folder was too big to pose on github. You can access the data using the following Dropbox link: 
https://www.dropbox.com/sh/fxcmtbz4o3tacz1/AABjQbeyg27zDh1chZxRDFcpa?dl=0

Link to Dropbox folder with lectures: (files are too big to upload on github)
https://www.dropbox.com/scl/fo/8eihkjrepirh7hs1aqpyd/ACna4v6LtyJ4OENDybgTsgA?rlkey=dxxmky405s3j4gvqvexsfywey&dl=0


## Learning outcomes:

On successful completion of this module, students will be able to:
1.	Understand common data format and database structures specific to representative fields of environmental science 
2.	Demonstrate technical competency in handling common data types routinely encountered in the environmental sciences and identify relevant open-source data repositories
3.	Identify and design suitable data analysis strategies that consider data types, data distribution constraints, strength, benefits and limitations of statistical and modelling tools and environmental dynamics.
4.	Understand the limitation of available data and data analysis products. Understand sources of errors and demonstrate ability to comprehensively characterize uncertainties and interpret results in the context of these uncertainties, including measurement errors, environmental uncertainties as well as errors stemming from the analytical procedure itself (e.g. calibration of analysis using synthetic data/models). 

## Description of contents:

This module will deliver the core knowledge and skills required for understanding, accessing, processing and analysing remote sensing data. 
This week, we will focus on: 
1. understanding the main principles of remote sensing
   1.1 Physics, sensor tech., resolution
   1.2 Digital raster image data, point ops & algebraic operations
   1.3 Colour coordinate transformations & PCA
   1.4 Radar remote sensing
   1.5 Terrain analysis and LiDAR
3. learn some tricks on how and where to access remote sensing data
4. introduce some basic concepts of geostatistics

The key objective of the course is to equip the students with the information and technical skills needed to design comprehensive data analysis strategies and deliver thorough analytical results that best exploit the data available considering differences in data types, spatio-temporal coverage and associated uncertainties and errors.  


## Tutorials:
There are some great introductory tutorials available on Github. The one we will be using is called the “Open Source Geoprocessing Tutorial”. You must work through it this week: the link is: 

* https://github.com/patrickcgray/open-geo-tutorial?tab=readme-ov-file 

This steps you through the basics of handling raster images (reading, stacking, reshaping), displaying images and histograms, creating and displaying spectral indices, using vector data (points, lines, polygons), and classification (supervised with training data and unsupervised) and, in the second tutorial, deep learning classification approaches (e.g. random forests, k-nearest neighbour, k-means etc) and Principal Component Analysis (PCA) which we will talk about later, as well as classification accuracy assessments. 

Some Python resources exist to help compute spectral indices: 
* https://github.com/awesome-spectral-indices/awesome-spectral-indices

For a set of spectral indices with GUI (... but I hope you will by now become a bit 'allergic' to GUI for data processing/manipulations! :) )
* https://github.com/rander38/Remote-Sensing-Indices-Derivation-Tool 

To get some more practice on some terrain analysis, use the following tutorial, which is part of the Earthpy tutorial set, which is excellent and comprehensive https://earthpy.readthedocs.io/en/latest/get-started.html# ):

* https://earthpy.readthedocs.io/en/latest/gallery_vignettes/plot_dem_hillshade.html

Also consider:
* https://www.earthdatascience.org/tutorials/get-slope-aspect-from-digital-elevation-model/ 

The EarthLab site has has a huge range of tutorials. For Time-Series analysis, try this:
* https://www.earthdatascience.org/courses/use-data-open-source-python/use-time-series-data-in-python/ 


## Supplementary/recommended reading and useful resources:
* [FREE TO DOWNLOAD] Jian Guo Liu and Philippa Mason, 2016, Image Processing and GIS for Remote Sensing – Techniques and Applications, Second Edition, 472p, ISBN: 978-1-118-72420-0, March 2016, Wiley-Blackwel. Contains all the mathematical background for image processing of all kinds of digital remotely sensed imagery. http://eu.wiley.com/WileyCDA/WileyTitle/productCd-1118724208.html 
![image](https://github.com/user-attachments/assets/b8f6ad4e-b28a-453b-9ff0-78268148d7f6)

* Multiple-point geostatistics: stochastic modeling with training images
https://www.wiley.com/en-gb/Multiple+point+Geostatistics%3A+Stochastic+Modeling+with+Training+Images-p-9781118662953

* Gonzalez, R. C., Rafael, C. at al., 2019, Digital Image Processing (pdf). 
* Jensen, J. R.2016, Introductory Digital Image Processing – A Remote Sensing Perspective.
* Richards, J. A., 2013, Remote Sensing Digital Image Analysis: an Introduction. (3rd Edition)
* Mather, P. M., 2011, Computer Processing of Remotely-Sensed Images, 4th edition
* Schowengerdt, R. A., 2006, Remote Sensing: Models and Methods for Image Processing
* Niblack, W., 1986, An introduction to digital image processing  (old but really good)

Plus there are many  resources (and ready code) available for EO applications. Check out:

* eo-learn https://pypi.org/project/eo-learn 
* GitHub.com/arcgeospatial/awesome-earthobservation-code 
* GitHub.com/sentinel-hub/eo-learn-workshop 
* GitHub.com/earthlab/earth-analytics-python-env
* ESE Jupyter notebooks (by Raul Adraeinsen)
* Earthdatascience.org/courses/earth-analytics-python
* Raster data format descriptors and drivers GDAL.org


## Lecture schedule

|Date                       | Lecture                             |Instructor  |Moderator   |
|---------------------------|-------------------------------------|------------|------------|
|2025-01-06 9:00-12:00 Mon  | Intro to remote sensing I          | Y Plancherel        | GTA         |
|2025-01-06 14:00-17:00 Mon | Intro to remote sensing II; GEE practical   | Y Plancherel; M Prasow-Emond       | GTA         |
|2025-01-07 9:00-12:00 Tue  | Spatial data; geostatistics         | Y Plancherel        | GTA         |
|2025-01-07 14:00-17:00 Tue | Open-Geo-Tutorial        | Y Plancherel; M Prasow-Emond      | GTA         |
|2025-01-08 9:00-12:00 Wed  | Research talks; Open-Geo-Tutorial | M Prasow-Emond; R Adriaensen     | GTA         |
|2025-01-08 14:00-17:00 Wed | Free                                | Y Plancherel        | GTA         |
|2025-01-09 9:00-12:00 Thu  | Mini-project: Nagazaki        | Y Plancherel        | GTA         |
|2025-01-09 14:00-17:00 Thu | Mini-project: Nagazaki          | Y Plancherel        | GTA         |
|2025-01-10 9:00-12:00 Fri  | self-study        |         |             |
|2025-01-10 14:00-16:00 Fri  | Quiz        |         |             |

## Assessment exercises
Assessment will be 100% by coursework/quiz. It is open book but absoluetly forbids use of any AI tools or internet resources, including translation softwares other than plain dictionaries. 

Questions will be distributed and submitted via GitHub Classroom on Friday. 

|Release Date         | Due Date            | Topic                             |
|---------------------|---------------------|-----------------------------------|
|2025-01-24 Fri 14:00 | 2025-01-24 16:00 Fri| Assessment, Environmental data weeks 1,2,3         |
