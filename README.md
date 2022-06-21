# Plant-Disease-Classification
Identification of plant health is the new challenging area for the researchers. One of the most important steps in automatic identification of plant diseases is to extract the infected region from the normal portion of the plant. Studying the infected leaves it has been observed that the greenness of the infected portion of the leaves changes significantly with respect to the normal leaves. Vegetation indices (VI) are some metric used for the remote sensing images to measure the greenness. Images of tomato leaves of both categories healthy and diseased captured with digital camera and resolution of 256x256 pixels forms the dataset. CNN model is used for identifying the health status of plants.

# Description
This project implements a CNN model to classify leaf images to determine the health of a plant.

The goal is to help novice plant owners determine if their plants are healthy or need some special attention. If the model can accurately classify an unhealthy plant, then users can take the next step to research and determine whether their plants are being over/under watered, receiving too much/too little sunlight, infested, etc.

# Methodology
## Step 1 - Image Acquisition:
This is the process of acquiring the images through a camera by going to the site or from other available sources such as image databases or online repositories. The captured images are in three colors, that is, Red, Green, and Blue (RGB), for which a color transformation structure is created, and a device-independent color space transformation is applied on it.

## Step 2 - Image Pre-processing:
To remove noise in an image, different pre-processing techniques are used. Clipping of leaf image is applied to extract the region of the image in which we are interested. The extracted plant leaf image is transferred to a digital system to remove the unnecessary areas. Some essential steps of pre processing are: Resizing the image, Noise removal from the image, enhancement and smoothing of the image.

## Step 3 - Image Segmentation:
This method of image processing is used to partition an image into significant components according to similar characteristics. Various methods are available for image segmentation such as boundary and spot detection algorithm, region and edge-based methods, Otsu’s method, thresholding techniques and k-means clustering, etc.

## Step 4 - Feature Extraction: 
It is a type of dimension reduction technique that effectively represent the useful part of the image. Various features such as texture, color, edges and morphology can be extracted for the detection of plant disease. Color co-occurrence method is used for feature extraction.

## Step 5 - Classifiers: 
Classifiers are used to identify and categorize the different diseases that occur on plant leaves based on obtained features. Several classifiers that have been used in earlier work to detect diseases in plants are K-nearest neighbors (K-NN), Support Vector Machines (SVM), Convolutional Neural Network (CNN) and Artificial Neural Network (ANN), etc.

# Use-case diagram
![image](https://user-images.githubusercontent.com/47741271/174048013-bee9539e-e481-487f-adcb-257a6bb233cb.png)

# Flow chart diagram
![image](https://user-images.githubusercontent.com/47741271/174811946-3e7fd096-30d5-493a-9bac-42b6653a717d.png)

# Conclusion and Future Scope
- To prevent losses, small holder farmers are dependent on a timely and accurate crop disease diagnosis. 
-	In this study, a pre-trained Convolutional Neural Network was fine-tuned, and the model was deployed online.
-	Agricultural department wants to automate the detecting the yield crops from eligibility process (real time). 
-	To automate this process by show the prediction end in web application or desktop application. To optimize the work to implement in AI environment. 
-	The proposed system is based on python and provides an accuracy of around 98%.
-	The accuracy and therefore the speed are often increased by use of Googles GPU for processing. 
-	The system is often installed on Drones in order that aerial surveillances of crop fields are often done.

# Languages used
Python

# Technologies/Platforms used
Google Collab

# Mentor
Dr. Vijendra Singh
