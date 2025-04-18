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
  https://github.com/Vignesh-Lakshmanasamy-mdx/CW2_PDE4434_Intelligent_Sensing.git
- Contents available in the folder is list in the image. Note : Keras and video file will not be available in both zip and github.
  ![image](https://github.com/user-attachments/assets/0eea74d8-3f4a-4f43-be8d-225591e4b424)

## Running the Program:

- Launch the Jupyter Notebook

      jupyter notebook

- Jupyter notebook opens in the browser and displays the file in the home folder.
- Navigate to the Folder where the unzipped file of the coursework is pasted.
- You can see the files and folders as in the image below,

  ![image](https://github.com/user-attachments/assets/801c0bef-cb97-4743-a240-2a284457d7dc)

- Initial step is to run the ML model and save the keras file, which is mandantory to run remaining scripts.
- To open the machine learning script - double click - **Uno_card_detection_ML.ipynb**
- After saving the keras file, proceed to run the **Uno_card_Detection_with_gui.ipynb** notebook, which contain the GUi interface for live and image prediction.
- If u have any trouble running the GUI file, u can use **1_card_detection.ipynb** and **2_card_detection.ipynb** for live detection without GUI
- To visualize the pre processing used in the project - open - **Preprocessing_final.ipynb**

## Executing the ML model - Uno_card_detection_ML.ipynb
- To run the machine learning and Evaluation
    - Follow the order of the notebook and Run the script in each step
        - Step 1 : Importing the required libraries
        - Step 2 : Routing the path of the dataset
        - Step 3 : Loading the dataset and preprocessing
        - Step 4 : Loading the data and reshaping to prepare for training process
        - Step 5 : Spliting the data for training and testing
        - Step 6 : CNN Model or MobileNetV2 Pre-trained Model in respective notebook 
        - Step 7 : Compiling the model
        - Step 8 : Training the model
        - Step 9 : Evaluating the accuracy of the model
        - Step 10 : Save the Model
            - Model will be saved as **uno_number_detection.keras**

- To run entire process in one click
    -  Go to Menu bar -> Run -> Run all cells
      ![image](https://github.com/user-attachments/assets/f6112c7f-04c5-4bfd-85e3-4f958c56d09e)

## Executing the Live and Image Prediction with GUI - Uno_card_Detection_with_gui.ipynb
- To run the Live and image prediction
    - Follow the order of the notebook and Run the script in each step
        - Step 1 : Importing all the required files
        - Step 2 : color detection program
        - Step 3 : Preprocessing image
        - Step 4 : GUI program for live and image detection

- To run entire process in one click
    -  Go to Menu bar -> Run -> Run all cells
      
    - GUI screenshot
 
      ![image](https://github.com/user-attachments/assets/3654cf56-1fa0-498e-bcd3-668c82ca51bd)

    - Live Detection screenshot
 
      ![image](https://github.com/user-attachments/assets/39aa14eb-2a1d-462c-977a-2098c7664450)
 
      ![image](https://github.com/user-attachments/assets/150f6fdb-f6d3-4116-a492-ff2bcdacf1b7)

    - Image prediction screenshot

      ![image](https://github.com/user-attachments/assets/7bf8e3f5-d198-40d2-8f9f-9010c9782dc3)

      ![image](https://github.com/user-attachments/assets/cfdef2ca-0adc-4a13-9a1e-83e0b4bf48ca)



## Executing the Live Prediction without GUI - 1_card_detection.ipynb (one card at a time)
- To run the Live prediction
    - Follow the order of the notebook and Run the script in each step
        - Step 1 : Function for Color detection
        - Step 2 : Live Prediction for 1 card at time

- To run entire process in one click
    -  Go to Menu bar -> Run -> Run all cells
      
  -Live Detection screenshot
  
    ![image](https://github.com/user-attachments/assets/0e6246f5-6ddf-4e82-9167-c64799b67012)

    ![image](https://github.com/user-attachments/assets/4e4d8d35-33c4-4883-a6be-347635dea053)



## Executing the Live Prediction without GUI - 2_card_detection.ipynb (two card at a time)
- To run the Live prediction of 2 cards at a time
    - Follow the order of the notebook and Run the script in each step
        - Step 1 : Function for cycle 1 of preprocessing
        - Step 2 : Preprocessing cycle 2
        - Step 3 : Live prediction for two cards at a time

- To run entire process in one click
    -  Go to Menu bar -> Run -> Run all cells
      
  - Live Detection screenshot (output is partially correct)
    
    ![image](https://github.com/user-attachments/assets/81dabd6d-1d10-4fad-92b8-da33d9eba907)

    ![image](https://github.com/user-attachments/assets/499bbec7-a1a5-496e-8d2e-967ae4ded997)



## Executing the Preprocessing demostration- Preprocessing_final.ipynb
- To run the preprocessing sample program
    - Follow the order of the notebook and Run the script in each step
        - Step 1 : Function for image ploting
        - Step 2 : All preprocessing and its output

- To run entire process in one click
    -  Go to Menu bar -> Run -> Run all cells


    
