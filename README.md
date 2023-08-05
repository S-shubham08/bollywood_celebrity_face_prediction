# Bollywood Celebrity Face Prediction

## Application Demo Page
![bollywoodcelebrityprediction](https://github.com/S-shubham08/bollywood_celebrity_face_prediction/assets/127888794/763e0411-733e-4eda-9d7a-6e1f46e8bd88)

## Project Description
- This project focuses on predicting Bollywood celebrity faces using the VGGFace model with the ResNet50 architecture. The VGGFace model is a deep learning model pre-trained on a large dataset of celebrity faces, and ResNet50 is used as the backbone for feature extraction.

- The objective is to recognize Bollywood celebrities and label the input images with the corresponding celebrity names.

## Data
- The dataset used for this project contains images of Bollywood celebrities and their corresponding labels.
- Prepare the dataset by organizing images in separate directories for each celebrity. Each directory should be named after the celebrity and contain images of that celebrity.

## Model Training
- Fine-tune the VGGFace model with the ResNet50 architecture using the prepared dataset. The model can be fine-tuned using transfer learning.
- Save the trained model for future predictions.

## Streamlit App
- Use Streamlit to create a user-friendly web application for Bollywood celebrity face prediction.
- Create a Python script app.py that loads the trained model and provides an interface for users to upload images and see the predicted celebrity names.
```
streamlit run app.py
```
