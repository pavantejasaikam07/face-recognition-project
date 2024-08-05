# face-recognition-project
This project implements a face detection and recognition system. The system uses Dlib for face detection and a neural network model for face recognition. The Jupyter notebook contains the complete code for processing, training, and evaluating the model.

# Face Detection and Recognition

## Overview

This project implements a face detection and recognition system. The system uses Dlib for face detection and a neural network model for face recognition. The Jupyter notebook contains the complete code for processing, training, and evaluating the model.

## Folder Structure

- `data/lfw-limited/`: Contains the original dataset with labeled faces.
- `data/processed/`: Contains preprocessed images with detected and cropped faces.
- `models/`: Contains the trained model, label encoder, and Dlib shape predictor.
- `notebooks/`: Contains the Jupyter notebook with the code.
- `docs/`: Contains project documentation.

## Setup and Installation

To set up the project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/pavantejasaikam07/face-recognition-project.git
   cd face-recognition-project
   pip install opencv-python dlib face_recognition numpy seaborn pillow pandas scikit-learn tensorflow joblib
   python version 3.8


