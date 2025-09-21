# Driver Drowsiness Detection System (DDDS)

A real-time computer vision project that detects driver fatigue by monitoring eye and face movements. The system uses Haar Cascade classifiers and a Convolutional Neural Network (CNN) to classify whether eyes are open or closed, and triggers an alert if drowsiness is detected to help prevent accidents.

## 🚀 Features
- Real-time face and eye detection using OpenCV  
- CNN model for eye state classification (open/closed)  
- Continuous monitoring of driver behavior  
- Instant alert system on drowsiness detection  
- Helps improve road safety  

---

## 🛠️ Tech Stack
- **Programming Language:** Python  
- **Libraries/Tools:** OpenCV, TensorFlow/Keras, NumPy  
- **Algorithms:** Haar Cascade Classifier, CNN  

---

## Working
The webcam captures the driver’s face in real-time.
Haar Cascade is used to detect face and eyes.
The CNN model classifies eye states (open/closed).
If eyes remain closed beyond a threshold, the system triggers an alert.

---

## 🔔 Future Improvements
Add yawning detection for better accuracy
Use advanced deep learning models for face landmark detection
Deploy on mobile or IoT devices for real-world applications

## 📌 Author
Developed by Rishi Singh 
🚗 Stay safe, drive safe!
