# Volumified

Volumified is a Python project that uses hand tracking to control the system's volume via a webcam. By detecting hand gestures, the system adjusts the volume in real-time based on the distance between the thumb and index finger.

## Features

- **Hand Gesture Control**: Adjust the system's volume using hand gestures.
- **Real-Time Processing**: Continuously tracks hand positions using a webcam.
- **Volume Range**: Controls volume within a specific range (e.g., -65 to 0 dB).

## Requirements

Before running the project, make sure you have the following Python packages installed:

- `opencv-python`
- `mediapipe`
- `pycaw`
- `numpy`

Installation
Clone the repository to your local machine:
bash
Copy code
git clone https://github.com/yourusername/volumified.git
Navigate into the project directory:
bash
Copy code
cd volumified
Install the necessary dependencies:
bash
Copy code
pip install -r requirements.txt
How to Use
Open a terminal and navigate to the project directory.
Run the main script to start tracking hand gestures and adjusting the volume:
bash
Copy code
python main.py
Make sure your webcam is connected and properly functioning.
Use hand gestures (distance between the thumb and index finger) to control the system volume.
Hand Gesture Control:
Thumb and Index Finger Distance: The distance between the thumb and index finger will control the system's volume.
Short distance = low volume.
Long distance = high volume.
Contributing
If you'd like to contribute to this project, feel free to fork the repository and create a pull request with your changes. All contributions are welcome!

Steps for Contributing:
Fork the repository.
Create a new branch (git checkout -b new-feature).
Make your changes and commit them (git commit -m 'Add new feature').
Push your changes to your fork (git push origin new-feature).
Create a pull request.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
The hand tracking functionality is powered by MediaPipe.
Volume control is managed using the PyCaw library.
