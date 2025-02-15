📌 Project Overview: How It Works
This real-time posture detection system is designed to assist stroke-affected individuals by continuously monitoring their posture using a USB webcam and a Raspberry Pi. The system ensures patient safety by detecting three key positions: sitting, standing, and lying down, and providing real-time notifications to caregivers.

🚀 How It Works:
1️⃣ Capturing Video – A USB webcam records real-time video of the patient.
2️⃣ Pose Detection – The system uses MediaPipe Pose to detect key body landmarks.
3️⃣ Posture Classification – The AI model analyzes the detected landmarks and determines if the person is sitting, standing, or lying down.
4️⃣ Alert System
    -If the person is sitting, a small notification is triggered.
    -If the person is standing, an alarm and notification are sent to the caregiver.
    -If the person is lying down, no alerts are sent.
5️⃣ Real-Time Response – The caregiver receives immediate notifications, enabling them to assist the patient and prevent potential falls.

🎯 Features  
- ✅ **Real-time posture detection** (Sitting, Standing, Lying Down)  
- ✅ **Instant notifications** for caregivers when the patient stands up or sits down  
- ✅ **Low-cost and efficient solution** using a **Raspberry Pi and USB webcam**  
- ✅ **Designed to enhance patient safety and prevent falls**  

🛠️ Tech Stack  
- **Hardware:** Raspberry Pi, USB Webcam  
- **Software:** Python, MediaPipe Pose, OpenCV  
- **Communication:** Real-time alerts for caregivers  

🔧 How to Implement This Project
1️⃣ Hardware Setup
    -Raspberry Pi (Recommended: Raspberry Pi 4)
    -USB Webcam for real-time video capture
    -Power Supply for the Raspberry Pi
    -Speakers (for audio alarms, optional)
2️⃣ Software Installation
    Ensure you have Python 3.x installed on the Raspberry Pi. Then, install the necessary libraries:
3️⃣ Running the System
    Download the project files onto your Raspberry Pi.
    Open a terminal and navigate to the project folder.
    Run the detection script.
    The system will start detecting posture and send notifications accordingly.
4️⃣ Customizing Alerts
    Modify the script to send alerts via email, SMS, or a mobile app based on your caregiver’s preferences.
    Integrate with IoT devices (e.g., smart lights or speakers) for enhanced alerts.

This system provides a low-cost, efficient, and real-time solution to enhance patient safety and caregiver response time.
