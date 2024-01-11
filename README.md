
# Vehicle Tracking System
## Overview
The Vehicle Tracking System is a Python-based project designed for real-time vehicle detection and tracking in video streams. The system utilizes the YOLO (You Only Look Once) object detection model for identifying vehicles in the input video. It incorporates the SORT (Simple Online and Realtime Tracking) algorithm to track the detected vehicles across frames.

## Project Initialization
To set up the project, follow these steps:

### Dependencies
The project relies on the following Python libraries:

Ultralytics
OpenCV (cv2)
cvzone
NumPy
Math
SORT (Simple Online and Realtime Tracking algorithm)
Ensure these libraries are installed in your Python environment before running the system.

## Object Detection and Tracking
The system performs the following steps in each video frame:

### YOLO Object Detection:

Utilizes the YOLO model (yolov8n.pt) to detect vehicles in the input frame.
Classifies detected objects into categories such as cars, buses, trucks, and motorcycles.
### SORT Tracking:

Initializes the SORT tracker with specific parameters (max_age, min_hits, iou_threshold).
Tracks the detected vehicles across frames, assigning unique IDs to each.
### Counting and Visualization:

Defines a counting line with specified coordinates (limits) to count vehicles.
Displays the count of detected vehicles and their unique IDs on the image.
Changes the color of the counting line to green when a new vehicle is counted.
### Graphics Overlay:

Overlays additional graphics on the image, enhancing the visualization of tracked vehicles.
## Usage
Video Input:

Set the input video file path in the VideoCapture object (../Videos/cars2.mp4).
Visualization:

Displays the processed video stream with real-time vehicle detection, tracking, and counting.
Output:

The system outputs a window named "Image" showing the processed video with overlaid graphics.
## Conclusion
The Vehicle Tracking System is a comprehensive solution for real-time vehicle detection, tracking, and counting. It leverages state-of-the-art object detection and tracking algorithms, making it suitable for various applications such as traffic monitoring and management.






