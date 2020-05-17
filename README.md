# Final Year Project - Satellite Image Segmentation

**Mentor:** Dr. Anjan Sarkar<br/>
**Team members:** MD. Asif Khan, Souradeep Kr. Basu, Rajdeep De, Ramanti Shaw, Sudip Bose

**About the project:**
Images are increasingly available from a variety of sources, including drones and conventional high altitude satellites. Our aim is to produce intervention-specific maps with the relevant features and in a short timeframe. Thus, the goal is to train a model that can annotate different features of the provided image.
We plan to use a U-Net model to classify different features of a provided image and run a script to detect the changes over time to detect and calculate the difference in between the current and the previous image.

## **Features achieved in Project I:**

In **Project I**, we used a satellite image consisting of different features such as trees, greenery, coastline and different water body levels. We used openCV and K-means algorithms for segmenting the different features of the satellite image.

**Dataset Source:** From Kaggle and also google images.

**Dependencies:**
Python >=3.6
openCV
Numpy
Matplotlib

**How to run:**
To run this project click on the following link:
[https://colab.research.google.com/github/reddevil1996/Project-Segmentation/blob/master/Satellite%20Image_Segmentation.ipynb](https://colab.research.google.com/github/reddevil1996/Project-Segmentation/blob/master/Satellite%20Image_Segmentation.ipynb)

## Determining the value of K:

Methods such as the elbow graph can be used to determine the value of K in K-means clustering. In our project we used K =7 for best results.

## **Our targets for project II:**

To achieve our target as mentioned in About the project we are currently working on a convolutional neural network (U-Net architecture) model for detecting different features of the image and check the difference between the two images over a time frame.
