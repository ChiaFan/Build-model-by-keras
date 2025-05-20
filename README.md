# Build-model-by-keras

Plastic Pellet Contamination Detection with Keras CNN

Overview

This project implements a contamination detection system for plastic pellet raw materials using a custom Convolutional Neural Network (CNN) built with Keras and TensorFlow. The model is trained to classify images of plastic pellets into five categories, identifying potential contamination based on visual characteristics. The system is designed for use in industrial quality control, enabling automated detection of anomalies in plastic pellet raw materials.

The code supports training a new model or loading a pre-trained model for inference, with data preprocessing and prediction capabilities for single test images. The model is trained on a dataset organized into class-specific folders, and predictions provide probabilities for each class.

Features
* Custom CNN Model: A Keras-based CNN with convolutional, pooling, and dense layers for contamination classification.
* Multi-Class Classification: Classifies plastic pellet images into five categories (e.g., clean, contaminated types).
* Data Preprocessing: Automatically resizes images to 256x256 pixels and normalizes pixel values.
* Training and Inference Modes: Supports training a new model or loading a pre-trained model for predictions.
* Dataset Flexibility: Uses image_dataset_from_directory to load images from a structured directory.
* Output: Provides class probabilities for test images, aiding in contamination analysis.

Requirements
* Python 3.8+
* TensorFlow 2.x
* Keras
* NumPy
* glob
