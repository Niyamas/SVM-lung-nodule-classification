# SVM-lung-nodule-classification
This project aims to classify lung nodules as benign or malignant using support-vector machines (SVM) in Python. The images used were from the 2015 LUNGx Challenge. This originally was a part of my capstone project for class. [Images download link](https://wiki.cancerimagingarchive.net/display/public/lungx+spie-aapm-nci+lung+nodule+classification+challenge)

A classification rate of 73% (ROC) was achieved.

1. The raw image data can be downloaded from: https://wiki.cancerimagingarchive.net/display/public/lungx+spie-aapm-nci+lung+nodule+classification+challenge
2. For the purposes of streamlining the preprocessing step, the images have automatically been cropped into 64x64 tiff images and cleaned so that only the nodule remains (parts of the lung and other objects have been removed). These can be found in the '6. Clean Crop' folder.
3. Place all ipynb files and csv files into a shared folder. You may need Jupyter Notebook to read the ipynb files and change the file paths.
4. Run the SVM Lung Nodule Classification.ipynb. file. This converts the image data into numbers so that it can be used in the SVM algorithm.

The methodology of the project is further explained in the Final Paper word document.
