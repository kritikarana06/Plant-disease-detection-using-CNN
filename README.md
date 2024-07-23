# Plant Disease Detection using CNN

This project uses a Convolutional Neural Network (CNN) to detect plant diseases from images. It is implemented in Python and utilizes TensorFlow and Streamlit for model inference and web app interface.
# Dataset
Link:https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset

The dataset used in this project is the Plant Village dataset. This dataset, accessible via [the Plant Village website or pertinent database], comprises an extensive collection of labeled photos depicting both healthy and diseased plants.
![image](https://github.com/user-attachments/assets/a14aaa65-1aa1-422d-a60a-6f313a3c4d67)

## Description

The project aims to classify plant diseases using images. A pre-trained CNN model is used to predict the class of the plant disease based on the input image. The model and class indices are loaded, and the prediction is performed using the provided image.

## Usage

1. Open the web app in your browser.
2. Upload an image of a plant leaf.
3. Click on the "Classify" button to predict the disease.

# Output
The streamlit web app interface:
![Screenshot (415)](https://github.com/user-attachments/assets/f5d14cae-854e-4c6f-9028-0571bddb5b2f)



## Code Overview

### `app.py`

This file contains the main logic of the application, including loading the model, preprocessing the image, and predicting the class of the uploaded image.


