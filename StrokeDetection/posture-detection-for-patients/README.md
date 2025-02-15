📌 Real-Time Posture Detection System

This real-time posture detection system assists stroke-affected individuals by continuously monitoring their posture using a USB webcam and a Raspberry Pi. It ensures patient safety by detecting three key positions: **sitting, standing, and lying down**, and provides real-time notifications to caregivers.

🚀 How It Works
1️⃣ Capturing Video – A USB webcam records real-time video of the patient.  
2️⃣ Pose Detection – The system uses MediaPipe Pose to detect key body landmarks.  
3️⃣ Posture Classification – An AI model analyzes the detected landmarks to determine if the person is **sitting, standing, or lying down**.  
4️⃣ Alert System  
   - Sitting: A small notification is triggered.  
   - Standing: An alarm and notification are sent to the caregiver.  
   - Lying Down: No alerts are sent.  
5️⃣ *Real-Time Response – Caregivers receive immediate alerts, enabling quick assistance to prevent falls.  

🎯 Features
- ✅ Real-time posture detection (Sitting, Standing, Lying Down)  
- ✅ Instant notifications for caregivers when the patient stands up or sits down  
- ✅ Low-cost and efficient solution using Raspberry Pi and USB webcam  
- ✅ Designed to enhance patient safety and prevent falls 

🛠️ Tech Stack
- Hardware: Raspberry Pi, USB Webcam  
- Software: Python, MediaPipe Pose, OpenCV  
- Communication: Real-time alerts for caregivers  

🔧 How to Implement This Project
1️⃣ Hardware Setup
- Raspberry Pi (Recommended: Raspberry Pi 4)
- USB Webcam for real-time video capture
- Power Supply for Raspberry Pi
- (Optional) Speakers for audio alerts

2️⃣ Software Installation
Ensure Python 3.x is installed on the Raspberry Pi, then install the necessary libraries:
```bash
pip install opencv-python mediapipe numpy
```

3️⃣ Running the System
- Download the project files to your Raspberry Pi.
- Open a terminal and navigate to the project folder.
- Run the detection script:
```bash
python posture_detection.py
```
- The system will detect posture and send alerts accordingly.

4️⃣ Customizing Alerts
- Modify the script to send alerts via **email, SMS, or mobile app notifications** based on caregiver preferences.
- Integrate with IoT devices (e.g., smart lights or speakers) for enhanced alerts.

---
This system provides a **low-cost, efficient, and real-time solution** to enhance patient safety and caregiver response time. 🚀

