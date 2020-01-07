# Face-Recognition

Author: Kaii Ono  
Date : 1/4/2020

I built a simple model using downloaded image files for differentiating two people that look similar. This project is organized as follows.
&nbsp; 

Step1.  
data processing: detect faces in each image and crop them as sample faces and stack them in matrix A

Step2.  
preparation for Step3: create variance space of faces

Step3.  
preparation for PCA: center the sample pictures at the origin and standardize the contrast

Step4.  
dimensionality reduction using SVD

Step5.  
data clustering: project each face on 3 basis

Step6.  
preparation for test

Step7.  
test: add two unexpected pictures(faces) to the plot

### files
face_recognition.ipynb: the jupyter notebook containing code  
newplot.png: result plot


### Result:
As newplot.png shows, the two people are nicely clustered, where red is Obama and blue is disguied person.  The unexpected pictures added are also separated nilcely.  
