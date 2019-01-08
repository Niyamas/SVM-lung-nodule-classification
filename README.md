# SVM-lung-nodule-classification
This project aims to classify lung nodules as benign or malignant using support-vector machines (SVM) in Python. The images used were from the 2015 LUNGx Challenge. This originally was a part of my capstone project for class. Images download link: https://wiki.cancerimagingarchive.net/display/public/lungx+spie-aapm-nci+lung+nodule+classification+challenge

A classification rate of 73% (ROC) was achieved.

1. Download the image data from: https://wiki.cancerimagingarchive.net/display/public/lungx+spie-aapm-nci+lung+nodule+classification+challenge
2. Run Auto Lung Nodule Cropping 2D.ipynb. The file automatically crops all the nodules into 64x64 images. Changes to the filepath will be required.
3. Run the 2D CT Image Preprocessing.ipynb. This step is not automated and will require additional work to be done to clean the images so that only the lung nodule remains.
4. Run the Feature Extraction and PCA v2.ipynb. This converts the image data into numbers to be fed to the SVM file.
5. Run SVM v2.ipynb to implement the support-vector machines algorithm for lung nodule classification.
