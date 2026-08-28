# Pothole Detection using YOLO11

A computer vision project for detecting potholes from road images, videos, and real-time webcam streams using **YOLO11 object detection**.

The goal of this project is to build an automated pothole detection system that can assist road inspection and maintenance by identifying damaged road areas using deep learning.

---

## Demo

The model can perform:

* Image-based pothole detection
* Video-based pothole detection
* Real-time webcam detection

Input:

```
Road Image / Video / Camera Feed
```

Output:

```
Detected potholes
+
Bounding boxes
+
Confidence scores
```

---

# Features

✅ YOLO11-based object detection
✅ Automated dataset preparation pipeline
✅ Custom pothole detection model training
✅ Image inference
✅ Video inference
✅ Real-time webcam detection
✅ GPU accelerated training
✅ Saved trained model weights

---

# Project Structure

```
Pothole-Detection/

│
├── models/
│   └── best.pt
│
├── notebooks/
│   └── Pothole_Detection.ipynb
│
├── test_images/
│
├── test_videos/
│
├── outputs/
│
├── train.py
├── inference.py
├── video_inference.py
├── webcam.py
│
├── requirements.txt
├── README.md
└── .gitignore