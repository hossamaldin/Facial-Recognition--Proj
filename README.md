# Face Recognition Attendance System

This project uses computer vision and face recognition to implement a real-time attendance system. It compares live webcam feed images with a dataset of known images and marks attendance when a known face is detected.

## Features

- Detects and recognizes faces using webcam feed.
- Compares detected faces with a known database.
- Marks recognized faces with a bounding box and label.
- Outputs real-time webcam display with annotations.

## Files

### `AttendanceProject.py`
- Main script that performs real-time face recognition using a webcam.
- Loads known face images from the `images/` directory.
- Encodes the faces and stores their names.
- Continuously checks for matching faces from webcam feed.

### `main.py`
- Demonstration script comparing two specific images (Elon Musk and a test image).
- Displays similarity and prints confidence score.


## Requirements

- Python 3.x
- OpenCV (`cv2`)
- NumPy
- `face_recognition` library


