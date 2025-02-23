#EmoDetect Web App

##Overview

This is a Flask-based web application that detects emotions from an uploaded facial image. The application uses a deep learning model trained on facial emotion datasets to classify emotions into categories like happy, sad, angry, surprise, and more.

##Features

Upload an image to detect facial emotions
Uses a pre-trained deep learning model (SuccessModel1) for emotion classification
Implements OpenCV for face detection
Returns the predicted emotion as a JSON response

##Technologies Used

Python
Flask
OpenCV (for face detection)
TensorFlow/Keras (for deep learning model)
HTML, CSS, JavaScript (for frontend)
Installation

#Prerequisites
Ensure you have the following installed:

Python 3.x
Flask
OpenCV (cv2)
TensorFlow/Keras
NumPy

##Usage:

Click the upload button to select an image.
The image is sent to the backend for processing.
The application detects a face and classifies the emotion.
The detected emotion is displayed as a response.

##File Structure:

/emotion-detection-app
│── server.py          # Flask application
│── emdetect.py        # Emotion detection logic
│── static/            # Static assets (CSS, JS, Images)
│── templates/
│   ├── home.html      # Frontend template
│── haarcascade_frontalface_alt.xml  # Face detection model
│── SuccessModel1/     # Pre-trained emotion detection model
│── requirements.txt   # Python dependencies
│── README.md          # Project documentation

##Screenshots:

<img width="1470" alt="Screen Shot 2023-04-01 at 5 12 17 PM" src="https://github.com/user-attachments/assets/5cc96647-7551-4b36-ba46-0e838c72ce2c" />
<img width="1470" alt="Screen Shot 2023-04-01 at 5 10 50 PM" src="https://github.com/user-attachments/assets/d52cc0d5-4fbd-4261-87a7-163c13df8576" />
<img width="1470" alt="Screen Shot 2023-04-01 at 5 10 43 PM" src="https://github.com/user-attachments/assets/cf99467b-717b-49d2-88bf-3a828e94a2b6" />
<img width="1470" alt="Screen Shot 2023-04-01 at 5 09 48 PM" src="https://github.com/user-attachments/assets/656a93ff-89cb-4b58-85d0-edc06551d675" />
<img width="1470" alt="Screen Shot 2023-04-01 at 5 09 40 PM" src="https://github.com/user-attachments/assets/e23e55da-042e-4de7-a14b-d0f15e492b33" />


##Future Enhancements:

Improve model accuracy with a larger dataset
Extend to real-time emotion detection using a webcam
Deploy the application on a cloud platform
