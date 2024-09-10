# AI Image Classifier

This project is an AI-powered image classifier web app built with Flask and TensorFlow. It allows users to upload an image, which the model will classify using a pre-trained VGG19 model.

![Image Classifier]((https://github.com/RzayevNihat/Image-Classifier/blob/main/readme%20image.png?raw=true)

## Features

- **Image Upload:** Upload an image via the web interface.
- **Prediction:** The app uses the VGG19 pre-trained model to predict the label of the uploaded image.
- **Real-Time Image Preview:** Users can see the uploaded image before submitting it for classification.

## Prerequisites

- Python 3.7+
- TensorFlow
- Flask
- Keras
- Numpy

## Usage
- Once the app is running, upload an image by clicking on the Choose File button.
- After selecting the image, click Predict! to classify the image.
- The prediction will be displayed below the uploaded image.

Model Information
The model used in this project is the VGG19 model, a 19-layer deep convolutional neural network trained on the ImageNet dataset.

For more details on the model architecture, visit: [VGG19 on Keras Documentation.](https://keras.io/api/applications/)
