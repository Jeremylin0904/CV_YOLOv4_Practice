# YOLOv4 Object Detection using Pre-trained Model

This repository contains a Python notebook demonstrating how to perform object detection using a pre-trained YOLOv4 model. YOLO (You Only Look Once) is a popular deep learning algorithm for real-time object detection. YOLOv4 is an improved version of the YOLO algorithm, offering better accuracy and speed.

## Notebook Overview

The provided notebook demonstrates how to utilize a pre-trained YOLOv4 model for object detection tasks. It covers the following steps:

1. Downloading the pre-trained YOLOv4 weights and configuration files from [https://github.com/AlexeyAB/darknet](https://github.com/AlexeyAB/darknet)
2. Loading the YOLOv4 model using OpenCV's `dnn` module.
3. Preprocessing an input image for inference.
4. Performing object detection on the input image using the YOLOv4 model.
5. Post-processing the detection results, including non-maximum suppression (NMS) to filter out overlapping bounding boxes.
6. Displaying the detected objects on the original image.
7. 
## Original Image

![Original Image](1811127-PH.jpg)
## Result

![Detected Objects](result.png)
