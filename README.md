# Hand Gesture Drawing Application

This Python project allows users to draw on a canvas using hand gestures. The application uses OpenCV and MediaPipe to detect the user's hand and enables drawing with different colors on a real-time canvas displayed on the webcam feed.

## Features

- Real-time drawing on the webcam feed.
- Color selection: Blue, Green, Red, and Yellow.
- Clear the canvas by touching the "CLEAR" button.
- Detects hand gestures to draw or clear using the index finger and thumb.
- The canvas updates live alongside the webcam video.

## Prerequisites

- Python 3.x
- OpenCV (`cv2`)
- NumPy (`numpy`)
- MediaPipe (`mediapipe`)

To install the required libraries, run:

```bash
pip install opencv-python mediapipe numpy
