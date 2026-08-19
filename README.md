# Surgical Tools Dataset

## Overview

The **Surgical Tools Dataset** is an object detection dataset designed for computer vision applications involving the detection and localization of surgical instruments in images.

The dataset is hosted on **Roboflow Universe** and contains **9,361 images** across **18 object classes**. It can be used to train and evaluate object detection models such as YOLO.

## Dataset Information

| Property          | Details                                                                  |
| ----------------- | ----------------------                                                   |
| Dataset Name      | Surgical Tools Dataset                                                   |
| Task              | Object Detection                                                         |
| Total Images      | 9,361                                                                    |
| Number of Classes | 18                                                                       |
| Train Set         | 6,545 images (70%)                                                       |
| Validation Set    | 1,880 images (20%)                                                       |
| Test Set          | 936 images (10%)                                                         |
| Image Size        | 416 × 416                                                                |
| Preprocessing     | Auto-Orient, Resize                                                      |
| Augmentation      | None                                                                     |

## Classes

The dataset contains **18 classes**, represented by the class IDs:

```text
0, 1, 2, 3, 4, 5, 6, 7, 8,
9, 10, 11, 12, 13, 14, 15, 16, 17
```

## Dataset Structure

When downloaded in YOLO format, the dataset follows a structure similar to:

```text
surgical-tools-dataset/
│
├── train/
│   ├── images/
│   └── labels/
│
├── valid/
│   ├── images/
│   └── labels/
│
├── test/
│   ├── images/
│   └── labels/
│
└── data.yaml
```

## Dataset Split

The dataset is divided into three subsets:

* **Training:** 6,545 images
* **Validation:** 1,880 images
* **Testing:** 936 images

This split allows the dataset to be used for model training, hyperparameter validation, and final performance evaluation.

## Preprocessing

This applies:

* Auto-orientation
* Image resizing
* Resize to **416 × 416 pixels**

No additional augmentations were applied in the referenced dataset version.

## Supported Formats
 Dataset is in multiple formats, including:

* YOLO
* YOLOv5
* YOLOv7
* YOLOv8
* YOLOv9
* YOLOv11
* YOLOv12
* COCO JSON
* Pascal VOC
* TFRecord
* YOLO Darknet
* Other formats

## Applications

This dataset can be used for:

* Surgical instrument detection
* Medical computer vision
* Object detection model training
* Surgical scene analysis
* Real-time surgical tool recognition
* Benchmarking object detection models

## Acknowledgement

This dataset was originally published by **Surgical Tools** for object detection research and computer vision applications.
