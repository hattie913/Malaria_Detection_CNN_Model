# Malaria_Detection_CNN_Model
## Introduction 
The traditional manual microscopic diagnosis is time-consuming and test results vary among observers. This project proposed a AI-based malaria detection model leveraging Convolutional Neural Networks (CNNs) to accurately identify malaria parasites (with accuracy of 98.4%) in blood smear miscroscopic images. 

The key questions for this project is to answer:
1) Can a CNN-based ML model detect parasite in red blood cells?
2) How accurately the CNN model can classify malaria infected and uninfected red blood cells?
3) How to implement the AI-based solution to streamline the malaria detection?
4) How the AI-based solution help monitoring Malaria prevalence?


The detected blood cell images are preprossed by HSV-transformed with Gaussian blurring, which reduce the image noise and enhance the capabilities of differentiating parasites from cell impurities under different microscopic lighting conditions. The proposed final CNN model is improved with LeakyReLU and Batch Normalization. 

### Data Description
There are a total of 24,958 train images and 2,600 test images (colored) m microscopic images. These images are of the following categories:

Parasitized: The parasitized cells contain the Plasmodium parasite which causes malaria (12582 cell images in training set, and 1300 cell images in test set)
Uninfected: The uninfected cells are free of the Plasmodium parasites (12376 cell images in training set, and 1300 cell images in test set)

Acknowledgements: This dataset was taken from the National Institutes of Health (NIH) website (https://www.nih.gov/, accessed on 11 August 2022) and contains 27,558 photos, including 15,376 uninfected cell images and 15,582 infected cell images.
