# Drowsy-Driver-detection

This project implements a drowsy driver detection system using the Haar Cascade algorithm. The system detects and alerts the driver when signs of drowsiness are observed, such as closed eyes or yawning. The project is implemented in Python using OpenCV.

**Features**
-Real-time detection: The system processes video feed from a webcam or other video source in real-time.
-Eye detection: Identifies whether the driver's eyes are closed for a prolonged period.
-Yawn detection: Detects yawning based on mouth movement.
-Alert system: Triggers an alert (sound or visual) when drowsiness is detected.

**Prerequisites**
-Python 3.x
-OpenCV (cv2)
-NumPy
-Pygame (for playing alert sounds)

**Installation**
**1) Clone the repository**:
   (git clone https://github.com/yourusername/drowsy-driver-detection.git
cd drowsy-driver-detection
)
**2)Install the required packages:**
(pip install -r requirements.txt)

**Usage****
**1)Run the detection script**
(python drowsy_driver_detection.py)
2)The system will start capturing video from your webcam. It will continuously monitor the driver for signs of drowsiness

**Haar Cascade Files**
The Haar Cascade algorithm relies on XML files containing the trained data for detecting specific features such as eyes, face, and mouth. You can download the pre-trained Haar Cascade files from the OpenCV GitHub repository:
-Haarcascades

**Alert System**
The alert system is triggered when the following conditions are met:
-Closed Eyes: If the eyes remain closed for more than a specified threshold, an alert is triggered.
-Yawning: If the mouth remains open for an extended period, indicating a yawn, an alert is also triggered.

**Contributing**
-Contributions are welcome! Please fork this repository and submit a pull request.

**License**
-This project is licensed under the MIT License - see the LICENSE file for details.

**Acknowledgments**
OpenCV for providing the Haar Cascade classifiers.
Community contributors for the pre-trained Haar Cascade XML files





