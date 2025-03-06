# Real-Time Emotion Detection with MQTT Publishing

**Author:** Harsithram R  
**Institution:** Kongu Engineering College  

This project captures live webcam video, detects faces, analyzes emotions in real time using DeepFace, and publishes targeted emotions (like fear, surprise, and sad) to an MQTT broker. A simple overlay of the detected emotion is displayed on the live video feed, and any detected targeted emotion is published to HiveMQ’s Cloud broker. The problem Statement is Make the Online class More Interactive.This projects detects the students emotions and the shows any targeted emotions it send it to the teacher through mqtt.

---

## Table of Contents

1. [Features](#features)  
2. [Project Workflow](#project-workflow)  
3. [Dependencies](#dependencies)  
4. [Contact](#contact)

---

## Features

- **Real-Time Capture**: Uses OpenCV to grab frames from the webcam.  
- **Face Detection & Emotion Analysis**: Relies on DeepFace to identify the dominant emotion.  
- **Targeted Emotion Filtering**: Publishes only specific emotions (e.g., fear, surprise, sad) via MQTT.  
- **Visual Overlay**: Displays the detected emotion text on the live frame.  
- **MQTT Integration**: Sends messages to a HiveMQ Cloud broker, making it easy to integrate with any subscriber dashboard.

---

## Project Workflow

1. **Capture Frame**: Continuously retrieve images from the user’s webcam.  
2. **Emotion Detection**: DeepFace analyzes each frame to determine the dominant emotion.  
3. **Filter Emotions**: If the emotion is one of the targeted types, publish it to MQTT.  
4. **Overlay & Display**: Overlay text on the image and display it in real time.


---

## Dependencies

- **Python 3.x**  
- **OpenCV (cv2)**  
- **NumPy**  
- **DeepFace**  
- **Pillow (PIL)**  
- **paho-mqtt**  
- **Google Colab (optional)**  


## Contact
Author: Harsithram R
Institution: Kongu Engineering College

If you have any questions, feel free to reach out via GitHub Issues or email at your-harsithram08@gmail.com.

Thank you for checking out this project! Happy coding.
