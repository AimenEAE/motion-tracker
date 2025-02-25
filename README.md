# Motion Tracker

## Overview
This is a simple motion tracking application using OpenCV and Python. It allows the user to select a point on a video feed, and the system will track its movement using the Lucas-Kanade Optical Flow method. The motion trail of the selected point is visualized on the screen.

## Features
- 📷 Uses OpenCV to capture video from the webcam.
- 🖱 Allows the user to select a point by clicking on the video feed.
- 🔍 Tracks the selected point's motion using optical flow.
- 🎨 Draws motion trails to visualize movement.
- ⏹ Press `ESC` to exit the application.

## Requirements
Ensure you have Python installed along with the following dependencies:

```bash
pip install opencv-python numpy
```

## Usage
### 1. Clone the repository
```bash
git clone https://github.com/your-username/motion-tracker.git
cd motion-tracker
```

### 2. Run the script
```bash
python motion_tracker.py
```

### 3. Interact with the application
- Click on the video window to select a point for tracking.
- The selected point will be tracked with a motion trail.
- Press `ESC` to exit.

## Code Explanation
- Captures video from the webcam using OpenCV.
- Converts frames to grayscale for processing.
- Uses `cv2.calcOpticalFlowPyrLK` for tracking movement.
- Updates and draws the motion trail on the frame.

