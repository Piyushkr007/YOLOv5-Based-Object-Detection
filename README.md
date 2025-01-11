# YOLOv5-Based-Object-Detection

This repository contains a Python script for detecting objects in video frames using the YOLOv5 object detection model. The script processes each frame of a video, detects objects, crops their images, and saves them to disk. It also generates a JSON file containing details about the detected objects and their sub-objects. Finally, the cropped images and JSON file are zipped for easy download.

## Features

- Detect objects in video frames using YOLOv5.
- Crop and save detected objects and sub-objects as images.
- Generate a JSON file with detection metadata.
- Create a ZIP file containing all cropped images and the JSON file.
- Display annotated frames in Google Colab.

## Requirements

This script requires the following dependencies:

- Python 3.x
- [YOLOv5](https://github.com/ultralytics/yolov5) model (loaded via PyTorch Hub)
- OpenCV
- Pandas
- Google Colab (for `cv2_imshow` and file downloads)

You can install the necessary dependencies using:

```bash
pip install torch torchvision pandas opencv-python
