# Object Detection with YOLOv8

This project involves training a YOLOv8 model for object detection on a custom dataset. The model is trained to detect five classes: gloves, goggles, helmet, jacket, and footwear. Annotations were created using 'labelImg,' and model performance was evaluated using Mean Average Precision (mAP) at 50% Intersection over Union (IoU).

## Project Overview

The objective of this project is to apply YOLOv8, a state-of-the-art object detection model, to a custom dataset of personal protective equipment (PPE) items. The model’s detection capabilities are fine-tuned for five specific classes, aiming for accurate real-time object detection in various scenarios.

## Classes

The custom dataset contains the following classes:
- Gloves
- Goggles
- Helmet
- Jacket
- Footwear

## Results

After training, the model achieved the following Mean Average Precision (mAP@50) scores for each class:
- **Gloves**: 67.4%
- **Goggles**: 11.8%
- **Helmet**: 88.7%
- **Jacket**: 74.3%
- **Footwear**: 84.5%
