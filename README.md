# CSC621-821-Team-River

Team Members:  

Ana	 

Douglas	

Eva	  - Team Lead 

Henry	

Phillip


Eric	- Dropped

IDE to use: We are using jupyter-notebook

ITK (C++) vs SimpleITK: we are using SimpleITK with python

How to share code: We are sharing through github

Brief summary of our code:

We are dealing with 3d images, focusing mainly on these two data sets below. We pull the data from the Cancer Imaging Archive, specifically the Medical Imaging Data Resource Center (MIDRC). We chose to focus on the lungs, and identifying and comparing different lungs in order to determine the likelyhood of being infected by COVID-19.

MIDRC-RICORD-1A-419639-000082 # This data set contains the infected lung

MIDRC-RICORD-1B-419639-000340 # This data set contains the normal lung

For segmentation:

We are able to segment out the lung, create a mask, change the color of it, and change the background to black. We are also able to create intensity histograms that we can infer information from. 

For registration:

We are able to align the images and compare the results. Specifically, we tried different algorithms such as Eular3DTransformation and used points to compare the two fixed and moving images.

For quantification:

-experimenting different values of system’s parameters to find the best values
-validating your registration results by checking the alignments visually/quantitatively
-compare different segmentation/registrations algorithms to determine which one perform best for the used data



