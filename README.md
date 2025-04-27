# Gesture-VolumeControl
This project enables real-time volume control of your system using hand gestures. It uses MediaPipe for hand tracking and Pycaw for controlling the system's audio volume. The application increases or decreases the volume based on the position of the index and middle fingers.

Features
Volume Control: Increase or decrease system volume using hand gestures.

Real-time Hand Tracking: Utilizes MediaPipe to track hand landmarks.

Python-based: Built using Python libraries like OpenCV, MediaPipe, and Pycaw.

Requirements
To run the project, you need the following Python packages:

opencv-python (for webcam capture)

mediapipe (for hand tracking)

pycaw (for controlling system audio volume)

You can install the required libraries using pip:

"pip install opencv-python mediapipe pycaw"

How It Works
Hand Tracking: The system detects your hand using MediaPipe and tracks the positions of your index and middle fingers.

Volume Adjustment: If your index finger is higher than the middle finger, the system increases the volume. If the middle finger is higher, the system decreases the volume.

Real-time Feedback: The webcam feed displays your hand with landmarks, and the system adjusts the volume accordingly.

How to Use
Clone the repository to your local machine.

Run the Python script:
"python gesture_volume_control.py"
The webcam window will open, and the system will start detecting hand gestures.

Raise or lower your index and middle fingers to control the volume.

Note
This script only works for systems with Windows OS, as it uses Pycaw for volume control.

Ensure that your camera is working properly for hand detection.

License
This project is open source and available under the MIT License.
