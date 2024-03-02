# Sign Language Recognition with CNN
![Sign Language Recognition](https://github.com/abhaashb0801/Sign-Language-Recognition-with-CNN/blob/main/sign_language_recognition.png)

## Overview
This project aims to recognize hand signs in real-time using computer vision and deep learning techniques. It includes two main components: 
1. Background subtraction and hand segmentation using OpenCV.
2. Hand sign recognition using a Convolutional Neural Network (CNN) implemented with Keras and TensorFlow.

## Contributor
- **Abhaash Kumar Bhiwaniya**

## Requirements
- Python 3.x
- OpenCV
- NumPy
- Matplotlib
- TensorFlow
- Keras

## Instructions
1. Clone this repository to your local machine.
2. Make sure you have the required libraries installed (mentioned in the requirements section).
3. Run `background.py` to capture the background (for hand segmentation) and save it as `background.jpg`.
4. Run `main.py` to start the real-time hand sign recognition.

## Project Structure
- `background.py`: Captures the background for hand segmentation.
- `main.py`: Real-time hand sign recognition using CNN.
- `best_model.h5`: Pre-trained CNN model for sign recognition.
- `sign_language_recognition.png`: Project overview image.

## Usage
1. Run `background.py` to capture the background image. This step is crucial for hand segmentation.
2. Run `main.py` to start real-time hand sign recognition using your webcam.

## How it Works
1. `background.py` captures the background without any objects.
2. `main.py` uses the captured background to perform background subtraction and isolate the hand from the background.
3. The isolated hand is then fed into the pre-trained CNN model (`best_model.h5`) for sign recognition.
4. The recognized sign label is displayed on the screen in real-time.

## Dataset
The dataset used to train the CNN model is not included in this repository. You can use any sign language dataset of your choice or collect your own data for training.

Certainly, here's the updated contribution section in the README:

## Contributor
- **Abhaash Kumar Bhiwaniya**
