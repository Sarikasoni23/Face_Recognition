# Real-Time Face Detection with OpenCV

A lightweight computer-vision project that performs **real-time face detection from a webcam feed** using Python and OpenCV.

> Note: the current implementation performs face **detection**, not biometric identity recognition or authentication.

## Features

- Captures live video from the default webcam
- Converts frames to grayscale for detection
- Uses OpenCV's pre-trained Haar cascade classifier
- Detects frontal faces in real time
- Draws bounding boxes around detected faces
- Exits cleanly when the user presses `q`

## Tech Stack

- Python
- OpenCV
- Haar Cascade Classifier

## Installation

```bash
pip install opencv-python
```

## Run

```bash
python main.py
```

Make sure a webcam is available to the application.

## Preview

![Face detection preview](images/demo.jpg)

## Possible Improvements

- Add confidence/quality controls
- Add face recognition using trained embeddings
- Add attendance or authentication workflows
- Add automated tests and configuration options
