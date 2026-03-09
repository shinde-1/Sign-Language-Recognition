# Sign Language Recognition Using Deep Learning

# Project Description
This project implements a real-time American Sign Language (ASL) recognition system 
using Convolutional Neural Networks (CNN). The system recognizes hand gestures 
captured through a webcam and converts them into corresponding alphabet letters.

# Problem Statement
People who are deaf and dumb rely on sign language for communication. 
However, most people do not understand sign language, creating a communication gap. 
This project aims to bridge that gap using deep learning-based sign recognition.

# Objectives
- Recognize ASL alphabets using CNN
- Perform image preprocessing and segmentation
- Train and test a deep learning model
- Provide real-time webcam-based predictions

# Technologies Used
- Python
- OpenCV
- TensorFlow / Keras
- PyTorch
- NumPy
- Matplotlib

# Dataset
Dataset: American Sign Language (ASL) Dataset  
Source: Kaggle  
Total Images: ~87,000  
Classes: 26 Alphabets + Space, Nothing, Delete  
Images per class: ~3000

# Model Architecture
- Convolution Layers
- ReLU Activation
- Max Pooling
- Fully Connected Layers
- Softmax Output

# Project Directory Structure
.
├── input
│   ├── asl_alphabet_test
│   │   └── asl_alphabet_test
│   │
│   ├── asl_alphabet_train
│   │   └── asl_alphabet_train
│   │       ├── A
│   │       ├── B
│   │       ├── C
│   │       └── ...
│   │
│   ├── preprocessed_image
│   │   ├── A
│   │   ├── B
│   │   ├── C
│   │   └── ...
│   │
│   └── data.csv
│
├── outputs
│
└── src
    ├── cam_test.py
    ├── cnn_models.py
    ├── create_csv.py
    ├── preprocess_image.py
    ├── test.py
    └── train.py
    
# Results

- Training Accuracy: ~98%
- Validation Accuracy: ~98%
- Real-time webcam detection supported



