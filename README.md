# Real-Time Emotion Detector

An AI-powered web application that analyzes a live webcam feed to detect and display facial emotions in real-time.

[GIF of the app in action]
*(Pro-tip: After you finish the app, record a short GIF of it working and replace this line with it. It makes a huge impact!)*

---

## 📖 About The Project

This project uses computer vision and deep learning to build a real-time emotion detection system. It captures video from a webcam, identifies faces in each frame using OpenCV, and feeds the facial region into a custom-trained Convolutional Neural Network (CNN) to predict the emotion.

The primary goal was to create an end-to-end AI application, from training a model on the well-known **FER2013 dataset** to deploying it in an interactive and user-friendly web interface.

### Key Features:
* **Real-Time Detection:** Processes the webcam feed live with minimal latency.
* **Face Detection:** Utilizes OpenCV's Haar Cascades to accurately locate faces.
* **Emotion Classification:** Classifies faces into one of seven emotions: **Happy, Sad, Angry, Fear, Disgust, Surprise,** and **Neutral**.
* **Interactive UI:** A clean and simple web interface built with Streamlit.

### 🛠️ Built With

This project was built using the following technologies:

* **Python**
* **TensorFlow / Keras** (for building and training the CNN model)
* **OpenCV** (for image processing and face detection)
* **Streamlit** & **Streamlit-WebRTC** (for the web application and real-time video)
* **NumPy** (for numerical operations)