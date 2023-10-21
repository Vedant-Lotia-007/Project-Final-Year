# Tomato Disease Classifier:

## Overview
The final year undergraduate project, Tomato Disease Classifier is an Android application developed to help farmers easily diagnose diseases affecting their tomato plants. Utilizing the power of Convolutional Neural Networks (CNNs) and a vast dataset of tomato plant images, this application achieves high accuracy rates in real-time disease classification. The application is backed by a FastAPI for efficient communication and uses a TensorFlow Lite model for seamless integration and performance on Android devices.

## Features
- Real-time tomato disease classification using images.
- Utilizes a highly accurate CNN model trained on a diverse dataset of tomato plant images.
- FastAPI backend ensures quick and efficient communication.
- The model is converted to TensorFlow Lite, making the app lightweight and efficient on Android devices.
- User-friendly interface designed for farmers, requiring no technical expertise.

## Prerequisites
- Android 8.0 (Oreo) or above
- Camera for taking pictures of tomato plants leaf.

## Installation


## Usage
1. **Capture or Upload an Image:**
   Open the app, capture a new image of a tomato leaf, or upload an existing image from the gallery.

2. **Get Instant Results:**
   The app will instantly classify the image and provide results, indicating the health of the plant and possible disease if present.

3. **Detailed Information and Recommendations (optional):**
   Users can view detailed information on the diagnosed disease and receive recommendations for treatment.

## Development
### Model Training
The CNN model is trained on a diverse dataset of tomato plant images to ensure high accuracy. The model is then converted into TensorFlow Lite format to make it mobile-friendly and ensure efficient performance on Android devices.

### FastAPI Backend
A FastAPI backend is implemented to ensure efficient communication and real-time results. The API receives image data, processes it, and returns the classification results instantly.

### Android Application
The Android app is built using Android Studio, ensuring compatibility with a wide range of Android devices. The user interface is designed with farmers in mind, making it intuitive and easy to use.

## Contact
For any queries, please feel free to raise an issue on this GitHub repository, or contact the maintainers directly.
]
