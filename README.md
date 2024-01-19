# Sign Recognition Project

## Overview
This project focuses on real-time sign recognition using a Convolutional Neural Network (CNN). The system captures video input from a webcam, processes the frames, and predicts the sign being displayed using a pre-trained CNN model.

## Requirements
Make sure you have the following dependencies installed:

- OpenCV (cv2)
- NumPy (numpy)
- Keras (keras)
- scikit-image (skimage)
- Pillow (PIL)
  
You can install them using the following command:  
        
    pip install opencv-python numpy keras scikit-image Pillow

## Usage
1. Download the pre-trained CNN model file, CNNmodel.h5, and place it in the project directory.
2. Run the main() function in the provided script to start the sign recognition system. Ensure that your webcam is connected and functioning properly.
3. A window will appear showing the webcam feed with a rectangular region of interest (ROI) where signs can be displayed. The predicted sign will be displayed on the top-right corner of the window.
4. Press 'q' to exit the application.


