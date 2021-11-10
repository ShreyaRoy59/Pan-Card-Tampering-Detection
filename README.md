# Pan-Card-Tempering-Detection

<p align="center">
  <img src="https://img.shields.io/badge/Machine%20Learning-brightgreen" />
  <img src="https://img.shields.io/badge/PYTHON%20-blue" />
  <img src="https://img.shields.io/badge/Computer%20%20Vision-brightgreen" />
</p>


Detecting fraud Pan Cards using computer vision to help organisations in verifying ID's of employees or customers.


<p align="center">
<img src="https://www.nec.com/en/global/solutions/biometrics/img/face/face_header_sd.jpg" width="800px">
</p>
 


The purpose of this project is to detect tampering/fraud of PAN cards using computer vision. This project will help the different organizations in detecting whether the Id i.e. the PAN card provided to them by their employees or customers or anyone is original or not.
## Table of Contents
- Overview
- Steps in the project
- Packages


## Overview
For this project we will calculate the structural similarity of the original PAN card and the PAN card uploaded by the user – This is the soul of this project we will discuss it thoroughly later in this blog.

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

* Skimage: Scikit-image, or ski-mage, is an open-source Python package, in this project most of the image processing techniques will be used via scikit-image
* imutils: Imutils are a series of convenience functions to make basic image processing functions such as translation, rotation, resizing, and displaying images easier with OpenCV.
* cv2: OpenCV (Open Source Computer Vision Library) is a library of programming functions. Here in this project major reading and writing of the image are done via cv2.
* PIL: PIL (Python Imaging Library) is a free and open-source additional library for the Python programming language that adds support for opening, manipulating, and saving many different image file formats.
