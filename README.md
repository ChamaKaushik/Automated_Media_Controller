# Automated_Media_Controller-Python Project
## Project Overview
The Automated Media Controller is a Python-based project that enables users to control a media player, such as YouTube or VLC, using hand gestures. By simply raising a specific number of fingers, users can perform actions like forwarding, rewinding, adjusting volume, or pausing/unpausing the video.

## Setup
* Install opencv
* Install mediapipe
* Install pyautogui

## Features
### Gesture Controls:
* 1 Finger: Forward
* 2 Fingers: Backward
* 3 Fingers: Volume Up
* 4 Fingers: Volume Down
* 5 Fingers: Pause/Unpause

## Libraries Used
* OpenCV: Used to capture video frames from the webcam.
* MediaPipe: Utilized for detecting hand landmarks and tracking finger movements.
* PyAutoGUI: Handles the execution of commands, such as controlling the media player based on detected gestures.

## How It Works
* Frame Capture: OpenCV reads frames from the webcam to capture the hand in real-time.
* Hand Detection: MediaPipe processes the captured frames to detect hand landmarks and identify the number of raised fingers.
* Gesture Interpretation: An algorithm is implemented to determine which action (e.g., forward, backward, volume up) should 
  be executed based on the number of fingers raised.
* Command Execution: PyAutoGUI sends the corresponding command to the media player.

## Usage
* Make sure your webcam is connected and working.
* Raise the corresponding number of fingers to control the media player as described in the features section.

## Contributions
Feel free to contribute by submitting issues or pull requests to improve the functionality or add new features.
