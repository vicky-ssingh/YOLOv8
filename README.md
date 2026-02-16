# YOLOv8 Local Video Object Detection 🎥

## 📌 Project Overview

This project demonstrates **real-time object detection using YOLOv8** on
a locally stored video file. The system processes each frame of the
video, detects objects, draws bounding boxes, and saves a fully
annotated output video.

This notebook is beginner-friendly and designed for Computer Vision
practical implementation.

------------------------------------------------------------------------

## 🎯 Objective

-   Run YOLOv8 on a local video
-   Detect objects frame-by-frame
-   Generate an annotated video output
-   Understand real-time object detection workflow

------------------------------------------------------------------------

## 🛠 Technologies Used

-   Python
-   Ultralytics YOLOv8
-   OpenCV
-   Jupyter Notebook

------------------------------------------------------------------------

## 📂 Project Structure

    project/
    │
    ├── yolov8_local_video_object_detection.ipynb
    ├── video.mp4                # Input local video
    ├── annotated_output.mp4     # Output annotated video
    └── runs/
        └── detect/
            └── your_custom_model/
                └── weights/
                    └── best.pt

------------------------------------------------------------------------

## ⚙ Installation

Install required libraries:

``` bash
pip install ultralytics
pip install opencv-python
```

------------------------------------------------------------------------

## ▶ How to Run

### Step 1: Open Notebook

Open the Jupyter notebook:

    yolov8_local_video_object_detection.ipynb

### Step 2: Provide video path

Update this line:

``` python
INPUT_VIDEO = "video.mp4"
```

Example:

``` python
INPUT_VIDEO = "C:/Users/YourName/Desktop/test.mp4"
```

### Step 3: Run cells

Run all cells step-by-step.

------------------------------------------------------------------------

## 🤖 Model Details

### Option 1: Pretrained Model

The notebook automatically loads:

    yolov8n.pt

### Option 2: Custom Model

If available:

    runs/detect/your_custom_model/weights/best.pt

------------------------------------------------------------------------

## 📊 Output

The system will generate:

-   Annotated video with bounding boxes
-   Labels and confidence scores
-   Display video inside notebook

Output file:

    annotated_output.mp4

------------------------------------------------------------------------

## 💡 Use Cases

-   Traffic monitoring
-   Security surveillance
-   Smart city systems
-   Retail analytics
-   Autonomous systems

------------------------------------------------------------------------

## 👨‍🎓 Academic Use

Suitable for: - Computer Vision practical - AI/ML project demo - Final
year project module

------------------------------------------------------------------------

## 🚀 Future Improvements

-   Real-time webcam detection
-   Multi-camera support
-   GPU acceleration
-   Custom dataset training
-   Deployment using Flask/Streamlit

------------------------------------------------------------------------

## 📧 Author

**Vicky Singh**\
AI & Data Science Enthusiast
