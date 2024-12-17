CNN for Image Classification: Cat vs Dog

Project Overview
This project involves building a Convolutional Neural Network (CNN) for image classification. The model is designed to classify images into two categories: cats and dogs. The CNN model is implemented using TensorFlow and Keras, and it uses a dataset of labeled cat and dog images to train and test the model.

1. Installations
This project was implemented using Python and TensorFlow/Keras. The relevant Python packages for this project are as follows:

TensorFlow: for building and training the CNN model
Keras: high-level neural networks API running on top of TensorFlow
NumPy: for numerical operations
Matplotlib: for visualizing the images and results
os: for file and directory handling
sklearn: for data preprocessing, splitting datasets 


2. Project Motivation
This project is aimed at classifying images of cats and dogs using a deep learning model, specifically a Convolutional Neural Network (CNN). The motivation behind this project is to explore image classification using deep learning techniques and to build a model that can accurately classify new images as either a cat or a dog.

The project answers the following questions:

Can a CNN model be trained to effectively classify images of cats and dogs?
How does image preprocessing, including data augmentation, affect the model's performance?

Summary of Findings:
The CNN achieved good performance in distinguishing between cats and dogs, with the accuracy of the model improving by using data augmentation techniques such as zooming, flipping, and shearing.
The model uses a simple architecture with convolutional and pooling layers, and it can predict new images with reasonable accuracy.

3. File Descriptions
This project contains the following files:

CNN for Image Classification.ipynb: Contains the code for building and training the CNN model.
README.md: This file containing the project documentation.

4. Results
Model Performance:
The CNN model is able to achieve satisfactory accuracy on the binary classification task (cat vs dog). The performance can be further improved using techniques like transfer learning or hyperparameter tuning. The further results are available in https://medium.com/@udayapriyaravikumar/building-a-convolutional-neural-network-for-image-classification-cddac29b46e6


Prediction Example:
For example, when a new image of a cat or dog is provided to the model, the model will predict the class with a probability greater than 0.5 for "Dog" and less than 0.5 for "Cat".

Prediction Visualization:
The input image is displayed with the prediction as the title, and the output along with the image is shown in the console.

5. How to Run the Project
Step 1: Clone the Repository
Step 2: Download the Dataset from the provided google drive link : https://drive.google.com/drive/u/1/folders/11QJSo_-fZS1cpB6B2GXHj9ccQy4UPKnI
Step 3: Install Dependencies
Step 4: Run the code file - train the model and test the prediction


