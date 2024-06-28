# Object Detection Using SSD MobileNet V3

This repository contains a project that performs object detection using the SSD MobileNet V3 model with OpenCV and TensorFlow. The model is used to detect objects in both images and videos using the COCO dataset.

## Project Overview

The project involves the following steps:

1. Loading the SSD MobileNet V3 model and configuration files.
2. Reading the class labels from a file.
3. Performing object detection on images.
4. Performing object detection on videos.
5. Displaying the detected objects with bounding boxes and labels.

## Requirements

- OpenCV
- matplotlib
- numpy

You can install the required packages using the following command:

```sh
pip install opencv-python matplotlib numpy

Dataset
The model used in this project is pre-trained on the COCO (Common Objects in Context) dataset. The COCO dataset contains 80 different object categories and is widely used for object detection tasks.
