# Pan-Card-Tempering-Detection

<p align="center">
  <img src="https://img.shields.io/badge/Machine%20Learning-brightgreen" />
  <img src="https://img.shields.io/badge/PYTHON%20-blue" />
  <img src="https://img.shields.io/badge/Computer%20%20Vision-brightgreen" />
</p>


## Detecting fraud Pan Cards using computer vision to help organisations in verifying ID's of employees or customers.


<p align="center">
<img src="https://www.nec.com/en/global/solutions/biometrics/img/face/face_header_sd.jpg" width="800px">
</p>
 


The purpose of this project is to detect tampering/fraud of PAN cards using computer vision. This project will help the different organizations in detecting whether the Id i.e. the PAN card provided to them by their employees or customers or anyone is original or not.
## Table of Contents
- Overview
- Steps in the project
- Packages


## Overview
For this project we will calculate the structural similarity of the original PAN card and the PAN card uploaded by the user. 
<!--   This is the soul of this project we will discuss it thoroughly later in this blog.-->

Similarly in this project with the help of image processing involving the techniques of computer vision we are going to detect that whether the given image of the PAN card is original or tampered (fake) PAN card.

## The steps in the project 
1. Import necessary libraries
2. Scraping the tampered and original pan card from the website
3. Scaling down the shape of the tampered image as the original image
4. Read original and tampered image
5. Converting an image into a grayscale image
6. Applying Structural Similarity Index (SSIM) technique between the two images
7. Calculate Threshold and contours and
8. Experience real-time contours and threshold on images


## Required packages

* <a href="https://scikit-image.org/docs/dev/api/skimage.html#:~:text=scikit%2Dimage%20(a.k.a.%20skimage%20),image%20processing%20and%20computer%20vision."> <b>Skimage </b> </a> : Scikit-image, or ski-mage, is an open-source Python package, in this project most of the image processing techniques will be used via scikit-image
* <a href= "https://github.com/PyImageSearch/imutils#:~:text=imutils-,A%20series%20of%20convenience%20functions%20to%20make%20basic%20image%20processing,Python%202.7%20and%20Python%203.">  <b>imutils </b> </a> : Imutils are a series of convenience functions to make basic image processing functions such as translation, rotation, resizing, and displaying images easier with OpenCV.
* <a href="https://pypi.org/project/opencv-python/"> <b>cv2 </b> </a> : OpenCV (Open Source Computer Vision Library) is a library of programming functions. Here in this project major reading and writing of the image are done via cv2.
* <a href="https://en.wikipedia.org/wiki/Python_Imaging_Library"> <b>PIL </b> </a> : PIL (Python Imaging Library) is a free and open-source additional library for the Python programming language that adds support for opening, manipulating, and saving many different image file formats.




## Summary
- Finding out structural similarity of the images helped us in finding the difference or similarity in the shape of the images.
- Similarly, finding out the threshold and contours based on that threshold for the images converted into grayscale binary also helped us in shape analysis and recognition.
- As our SSIM is ~31.2% we can say that the image user provided is fake or tampered with.
- Finally, we visualized the differences and similarities between the images by displaying the images with contours, difference, and threshold.
