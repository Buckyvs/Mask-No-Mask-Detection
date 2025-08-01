# Mask vs. No Mask Face Detection

This project implements a deep learning-based face mask detection system that identifies whether a person is wearing a mask or not in images or videos. Leveraging computer vision and convolutional neural networks, it provides an effective solution for safety monitoring, particularly for public health compliance.

## Features

- Detects faces in images or video frames
- Classifies detected faces as **wearing a mask** or **not wearing a mask**
- Visualizes results with bounding boxes and labels right on the images
- Easy to train and test using your own custom datasets
- Modular, extensible codebase

## Installation

Follow these steps to set up the project locally:


*Make sure you have Python 3.x installed on your system.*

## Usage

1. **Open the Jupyter notebook**:

    ```
    jupyter notebook mask_noMask_detection.ipynb
    ```

2. **Run the notebook cells** sequentially to:
    - Load data
    - Train the model
    - Test detection on sample images or video

3. **Test with your own data** by updating the corresponding paths inside the notebook.

## Configuration

**Optional:** Customize the following directly in the notebook:
- Dataset paths for training and testing
- Model parameters (epochs, batch size, etc.)
- Detection thresholds for face and mask classification
- Output visualization styles

## Technologies Used

- Python 3.x
- TensorFlow and Keras (deep learning frameworks)
- OpenCV (image processing and face detection)
- NumPy and Matplotlib (data handling and visualization)
- Jupyter Notebook (interactive development environment)
