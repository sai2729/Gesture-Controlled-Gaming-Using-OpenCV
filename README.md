# Gesture-Controlled-Gaming-Using-OpenCV
Python project using OpenCV and Numpy to control a car racing game with hand gestures. The game screen is divided into sections that detect specific colors to simulate keyboard inputs, providing a virtual and interactive driving experience.

### How It Works:
- **Color Detection & Tracking:** The `color.py` script sets the range of HSV values for the Blue color, which is used for detecting the object in real-time.
- **Gesture-Based Controls:** The gestures detected by the color tracking system are mapped to specific in-game actions using the `directkeys.py` script.
- **Simulating Keyboard Inputs:** The key press and key release functions are handled by the `directkeys.py` file.

I'm using a MacOS and Spyder to run my project. This code will be compatible with any game on MacOS. If you are using WindowsOS, you might have to modify the `directkeys.py` file.

Follow the steps in the `requirements.txt` file to get the setup ready. First, run the `color.py` and `directkeys.py` files to set them up and make sure they're working correctly. Then, run `controlling_steer.py` to get the output window.

## Features
- Real-time color detection and tracking using OpenCV.
- Gesture-based control system to steer the car, accelerate, and brake.
- Simulates keyboard inputs based on detected gestures.

## Installation

### Prerequisites
- Python 3.5 (recommended to use Anaconda)
- Webcam

### Required Libraries
Install the necessary libraries by running the following commands:

```bash
conda create -n gaming-simulator python=3.5
conda activate gaming-simulator
pip install -r requirements.txt
