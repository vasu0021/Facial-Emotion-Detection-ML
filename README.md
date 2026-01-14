#  Facial Emotion Detection System

This project is a real-time facial emotion detection system built using Python, OpenCV, and a pre-trained deep learning model. The application captures webcam video, detects faces, and classifies facial expressions into emotions like Happy, Sad, Angry, Surprised, and Neutral using a Flask web interface.

##  Project Objectives

- Detect human faces from webcam input in real-time
- Classify detected faces into predefined emotion categories
- Build a user-friendly web app using Flask
- Demonstrate the integration of computer vision and deep learning

##  Features

- Real-time webcam emotion detection
- Emotion prediction using a pre-trained CNN model
- Lightweight web interface built with Flask
- Simple, fast, and interactive

##  Technologies Used

- **Python**
- **OpenCV** – Face detection and video capture
- **Keras / TensorFlow** – Deep learning model for emotion classification
- **Flask** – Web framework for UI
- **NumPy & Pandas** – Data processing

##  Emotions Detected

- Happy 
- Sad 
- Angry  
- Surprised  
- Neutral 

##  How It Works

1. Webcam captures video stream
2. OpenCV detects faces in each frame
3. Each detected face is processed and resized
4. The CNN model predicts the emotion
5. Prediction is displayed in the live video feed via Flask

##  How to Run the Project

```bash
# Clone the repository
git clone https://github.com/vasu0021/facial-emotion-detection.git

# Navigate to the project folder
cd facial-emotion-detection

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the Flask app
python app.py

# Open your browser and go to http://127.0.0.1:5000
