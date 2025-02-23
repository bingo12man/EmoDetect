# EmoDetect Web App

## Overview:<br/>
This is a Flask-based web application that detects emotions from an uploaded facial image and plays music based on the detected emotion using Spotify. The app uses a deep learning model (SuccessModel1) for facial emotion classification and integrates Spotify to suggest and play songs accordingly.

## Features:

✅ Upload an image to detect facial emotions

✅ Uses a deep learning model for classification

✅ Detects emotions like happy, sad, angry, surprise, neutral, etc.

✅ Automatically plays music from Spotify based on the detected emotion

✅ Implements OpenCV for face detection

## Technologies Used:

1. Python

2. Flask

3. OpenCV (for face detection)

4. TensorFlow/Keras (for deep learning model)

5. Spotify API (for music playback)

6. HTML, CSS, JavaScript (for frontend)

## Prerequisites:

Ensure you have the following installed:

- Python 3.x

- Flask

- OpenCV (cv2)
  
- TensorFlow/Keras

- NumPy

- Spotify API credentials (Client ID & Secret)

## Usage:

+ Click the upload button to select an image.

+ The image is sent to the backend for processing.

+ The application detects a face and classifies the emotion.

+ The detected emotion is displayed as a response.

## Screenshots:

<img width="1470" alt="Screen Shot 2023-04-01 at 5 12 17 PM" src="https://github.com/user-attachments/assets/5cc96647-7551-4b36-ba46-0e838c72ce2c" /><br/>

<img width="1470" alt="Screen Shot 2023-04-01 at 5 10 50 PM" src="https://github.com/user-attachments/assets/d52cc0d5-4fbd-4261-87a7-163c13df8576" /><br/>

<img width="1470" alt="Screen Shot 2023-04-01 at 5 10 43 PM" src="https://github.com/user-attachments/assets/cf99467b-717b-49d2-88bf-3a828e94a2b6" /><br/>

<img width="1470" alt="Screen Shot 2023-04-01 at 5 09 48 PM" src="https://github.com/user-attachments/assets/656a93ff-89cb-4b58-85d0-edc06551d675" /><br/>

<img width="1470" alt="Screen Shot 2023-04-01 at 5 09 40 PM" src="https://github.com/user-attachments/assets/e23e55da-042e-4de7-a14b-d0f15e492b33" />



## Future Enhancements:

+ Improve model accuracy with a larger dataset

+ Extend to real-time emotion detection using a webcam

+ Deploy the application on a cloud platform
