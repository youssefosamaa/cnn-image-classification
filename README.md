# Cats vs Dogs Image Classification using CNNs

A deep learning project focused on image classification using Convolutional Neural Networks (CNNs) with TensorFlow and Keras.

The model classifies images of cats and dogs by learning visual patterns such as edges, textures, and shapes from image data.

---

## Project Overview

This project demonstrates a complete deep learning workflow for computer vision tasks, including:

- Image preprocessing and augmentation
- Building a CNN architecture
- Model training and validation
- Performance evaluation
- Single image prediction

The project serves as a practical introduction to image classification using deep learning techniques.

---

## Dataset

The model was trained on a Cats vs Dogs image dataset containing:

- Training Set: 8000 images
- Test Set: 2000 images

Classes:
- Cat
- Dog

---

## Workflow

### 1. Data Preprocessing
- Rescaled image pixel values
- Applied data augmentation techniques:
  - Shear transformation
  - Zoom augmentation
  - Horizontal flipping

### 2. CNN Architecture
Built a Convolutional Neural Network using:

- Conv2D layers
- MaxPooling2D layers
- Flatten layer
- Dense fully connected layers
- Sigmoid output layer for binary classification

### 3. Model Training
- Optimizer: Adam
- Loss Function: Binary Crossentropy
- Evaluation Metric: Accuracy
- Epochs: 25

### 4. Model Evaluation
Evaluated training and validation performance using accuracy and loss metrics.

### 5. Prediction
Implemented single image prediction for unseen cat and dog images.

---

## Model Performance

- Training Accuracy: ~86%
- Validation Accuracy: ~83%

The model successfully learned meaningful visual features and achieved solid classification performance on unseen images.

---

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Key Skills Demonstrated

- Deep Learning
- Computer Vision
- Convolutional Neural Networks (CNNs)
- Image Preprocessing
- Data Augmentation
- Model Training & Evaluation
- Binary Image Classification

---

## Future Improvements

Possible future enhancements include:

- Transfer Learning using pretrained models
- Hyperparameter tuning
- Dropout regularization
- Batch normalization
- Confusion matrix analysis
- Model deployment using FastAPI or Streamlit

---

## Dataset Sources

Example datasets that can be used with this project:

- https://www.kaggle.com/datasets/bhavikjikadara/dog-and-cat-classification-dataset
- https://www.kaggle.com/datasets/samuelcortinhas/cats-and-dogs-image-classification
