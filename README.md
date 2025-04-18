# **PDE4434 – Intelligent_Sensing**

# **Coursework 2 (CW2)**

# **Task: Uno card Color and Number Detection using Computer Vision**

## Project Overview:

This project aims to detect the color and number of UNO cards using image processing and a custom Convolutional Neural Network (CNN). The system preprocesses card images by applying grayscale conversion, thresholding, contour detection, and alignment techniques to isolate the oval region in the center of the card. After cleaning the background and removing noise, the processed image is passed to a custom-trained CNN model that accurately classifies the number and symbol on the card (0–9) on the card. Color of the card is detected using HSV value.

## System requirements :

- python 3.8 or above
- If Python not installed. Please download and install from https://www.python.org/downloads/

- PIP 
- If Pip not installed. Please download and install from https://packaging.python.org/en/latest/tutorials/installing-packages/

- Jupyter Notebook
- If Jupyter Notebook not installed, use the below code to install in the windows powershell
  
             pip install notebook

- Libraries like TensorFlow, Keras, OpenCV, Numpy, Matplotlib, Pathlib, Sklearn

              pip install tensorflow keras opencv-python numpy matplotlib scikit-learn pathlib PyQt6

## Downloading the file and dataset:

- Download the Zip file of the coursework and unzip it, place it in the desired folder.
- Click the github repository link below and download the file, place it in the desired folder or location in the system.
  
