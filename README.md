# Face Detection using YOLOv8



In this project, I used YOLOv8 to detect objects and faces in both images and live webcam video. I learned how to load AI models, read images, access the webcam using OpenCV, and display the detection results in real time.

## Features

- Detect objects in an image
- Detect faces in an image
- Real-time face detection using webcam
- Real-time object detection using webcam
- Display detection results with bounding boxes

## AI Models Used

### 1. YOLOv8n
- Used for object detection
- Detects objects like people, cars, dogs, cats, bottles, chairs, and many more
- Lightweight and fast model

Model:
```
yolov8n.pt
```

### 2. YOLOv8 Face Model
- Used only for face detection
- Detects human faces with good accuracy

Model:
```
yolov8m-face.pt
```

## Technologies Used

- Python
- OpenCV
- Ultralytics YOLOv8
- Jupyter Notebook

## Libraries

```python
import cv2
from ultralytics import YOLO
```

## Project Structure

```
face_detection/
│
├── face_detection.ipynb
├── demo.jpg
├── demo2.jpg
├── demo6.jpeg
├── demo7.jpeg
├── demo8.jpeg
├── demo9.jpeg
├── demo10.jpg
├── yolov8n.pt
├── yolov8m-face.pt
└── README.md
```

## How It Works

### Image Detection

1. Load an image using OpenCV.
2. Load the YOLOv8 models.
3. Detect objects.
4. Detect faces.
5. Draw bounding boxes.
6. Display the final image.

### Live Webcam Detection

1. Open the webcam using OpenCV.
2. Capture video frames.
3. Run object detection.
4. Run face detection.
5. Draw bounding boxes.
6. Show the result in real time.
7. Press **x** to close the webcam window.

## Installation

Clone the repository

```bash
git clone https://github.com/your-username/face-detection-yolov8.git
```

Go to the project folder

```bash
cd face-detection-yolov8
```

Create a virtual environment (optional)

```bash
conda create -n detection_env python=3.12
conda activate detection_env
```

Install the required libraries

```bash
pip install ultralytics opencv-python jupyter
```

## Run the Project

For image detection

```bash
jupyter notebook
```

Open

```
face_detection.ipynb
```

For webcam detection

Run the webcam section of the notebook.

Press **x** to exit.

## What I Learned

- How OpenCV reads images
- How to use the webcam with Python
- How YOLOv8 works
- Difference between object detection and face detection
- How to load AI models
- How to draw detection boxes
- How to use Jupyter Notebook
- Basic Computer Vision concepts

## Future Improvements

- Save detected images
- Save webcam video
- Count the number of people
- Add confidence score on detections
- Improve detection speed
- Build a simple desktop application

## Author

**Om**

