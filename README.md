#**🚗 Driver Monitoring System (ADAS-Like)**

**Overview**

A real-time Driver Monitoring System built using Python, OpenCV, and MediaPipe to detect driver fatigue and distractions. The system analyzes facial landmarks to identify drowsiness, microsleep, yawning, gaze direction, and phone-related distractions, helping improve road safety.

**Features**

👁️ Drowsiness Detection

😴 Microsleep Detection

😮 Yawning Detection

👀 Gaze Tracking (Left/Right/Forward)

📱 Phone Distraction Detection

📊 PERCLOS Calculation

🔔 Real-Time Audio Alerts


**Technologies Used**

Python

OpenCV

MediaPipe

NumPy


**Installation**

pip install -r requirements.txt

python driver_monitoring.py


**⚙️ Project Workflow**

1.Capture live video from the webcam.

2.Detect facial landmarks using MediaPipe Face Landmarker.

3.Extract eye, iris, mouth, nose, and chin landmarks.

4.Calculate:

  - Eye Aspect Ratio (EAR)
  
  - Mouth Aspect Ratio (MAR)
  
  - PERCLOS

5.Analyze:

 
  - Eye closure duration

  - Blink patterns

  - Yawning behavior

  - Gaze direction

  - Head position

6.Detect fatigue and distraction events.

7.Trigger visual and audio alerts when unsafe conditions are identified.

8.Display the driver's current state in real time.


**Applications**

Driver Safety Monitoring

Smart Vehicles

ADAS Systems

Fatigue Detection Research

**Author**

Peddolla Harika
