# Object Tracker using OpenCV and Python

A versatile object tracking application built with Python. This allows users to run a lightweight, CPU-based tracker using OpenCV's DNN module and YOLOv4.

## ✨ Features

*   **Real-Time Detection:** Generates accurate bounding boxes using YOLO architectures.
*   **Object Tracking Logic:** Calculates center points and tracks pixel movement between frames to assign and maintain unique vehicle IDs.

## 🛠️ Installation & Setup

### 🅰️ CPU Setup (OpenCV & YOLOv4)
The CPU tracker specifically requires OpenCV 4.x
```
pip install "opencv-python<5" numpy
```
Download the official [YOLOv4 weights file](https://github.com/AlexeyAB/darknet/releases/download/darknet_yolo_v3_optimal/yolov4.weights)

## 📂 Project Structure
ObjectDetectionProject/     <br>
├── main.py         <br>
├── object_detection.py      &emsp;&emsp;&emsp; # CPU YOLOv4 Logic        <br>
└── dnn_model/               &emsp;&emsp;&emsp;&emsp;&emsp;&emsp; # Required for CPU only   <br>
&emsp; ├── classes.txt       <br>
&emsp; ├── yolov4.cfg        <br>
&emsp; └── yolov4.weights    <br>   
