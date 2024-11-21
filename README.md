# Drowsiness-Detection-ML
 A machine learning-based system to detect driver drowsiness in real-time, aiming to enhance road safety by providing timely alerts.
# Drowsiness Detection System Using Machine Learning

## Introduction
The **Drowsiness Detection System** is an advanced application leveraging machine learning and computer vision to prevent accidents caused by driver fatigue. The system processes live video input to analyze facial landmarks and detect signs of drowsiness, such as prolonged eye closure and yawning. Once drowsiness is detected, the system provides real-time alerts to ensure driver safety.  

This project is ideal for integration into modern vehicle safety systems or as a standalone application for long-distance drivers and fleet management systems. It aims to save lives and reduce road accidents caused by human errors related to fatigue.

---

## Key Features
- **Real-Time Detection:** Processes live video input to monitor facial activity continuously.  
- **Facial Landmark Analysis:** Utilizes advanced algorithms to track eye movements, blinks, and yawning frequency.  
- **Alerts and Notifications:** Issues visual and audio alerts to the driver when drowsiness is detected.  
- **Efficient and Lightweight:** Optimized for deployment on various platforms, including desktops and embedded systems.  
- **Customizable Parameters:** Sensitivity and thresholds can be adjusted for different use cases.

---

## Demo
![Demo of Drowsiness Detection](images/demo.gif)  
[Click here to watch a demo video](https://youtu.be/demo-link)

---

## Technologies Used
### **Programming Languages and Tools:**
- **Python:** Core programming language used for development.  
- **OpenCV:** For real-time image processing and facial landmark detection.  
- **Dlib:** For detecting and analyzing facial landmarks.  
- **Scikit-learn:** Machine learning library for training and prediction.  
- **NumPy and Pandas:** For numerical computations and data manipulation.  

### **Hardware Requirements:**
- A webcam or camera module for video input.  
- A computer or Raspberry Pi (optional) for deployment.

---

## Project Workflow
1. **Face Detection:**  
   The system detects the driver's face using Haar cascades or a pre-trained Dlib model.  
   
2. **Facial Landmark Detection:**  
   68 facial landmarks are identified using Dlib’s shape predictor.  
   
3. **Eye Aspect Ratio (EAR):**  
   Calculates the ratio between eye width and height to detect eye closure.  

4. **Yawning Detection:**  
   Uses mouth aspect ratio to identify yawning based on the height and width of the mouth.  

5. **Alert System:**  
   If drowsiness criteria are met (e.g., low EAR for a specific duration), the system triggers an audio and visual alert.  

---

## Installation and Setup
Follow these steps to set up and run the project:

### **Step 1: Clone the Repository**
Clone the repository to your local system:  
```bash
git clone https://github.com/username/Drowsiness-Detection-ML.git
cd Drowsiness-Detection-ML
